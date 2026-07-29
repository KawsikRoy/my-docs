<script>
  function checkPassword() {
    const password = prompt("Enter password to view this documentation:");
    const correctPassword = "1234"; // Change this
    if (password !== correctPassword) {
      document.body.innerHTML = "<h1>Access Denied</h1>";
    }
  }
  checkPassword();
</script>

# Welcome to My Docs

This is my documentation site.
