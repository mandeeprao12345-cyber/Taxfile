<script>

const scriptURL = "https://script.google.com/macros/s/AKfycbxuD8mCPaiOTJvq2xP63P_xTTJVT-EJY3PdAuDnRjezEupmL1-ULbFgF1eoNrVK5HSM/exec";

const form = document.getElementById("taxForm");

const submitBtn = document.getElementById("submitBtn");

const successMessage = document.getElementById("successMessage");

const errorMessage = document.getElementById("errorMessage");

form.addEventListener("submit", async (e) => {

  e.preventDefault();

  submitBtn.disabled = true;

  submitBtn.innerText = "Submitting...";

  successMessage.style.display = "none";

  errorMessage.style.display = "none";

  const formData = {

    name: document.getElementById("name").value,

    phone: document.getElementById("phone").value,

    email: document.getElementById("email").value,

    filingType: document.getElementById("filingType").value

  };

  try {

    const response = await fetch(scriptURL, {

      method: "POST",

      body: new URLSearchParams(formData)

    });

    const result = await response.text();

    console.log(result);

    if(result.includes("Success")) {

      successMessage.style.display = "block";

      form.reset();

    } else {

      errorMessage.style.display = "block";

      console.log(result);

    }

  } catch(error) {

    console.error(error);

    errorMessage.style.display = "block";

  }

  submitBtn.disabled = false;

  submitBtn.innerText = "Submit Details";

});

</script>
