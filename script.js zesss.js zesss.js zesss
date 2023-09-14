document.addEventListener("DOMContentLoaded", function () {
    const loginForm = document.getElementById("login-form");

    loginForm.addEventListener("submit", function (event) {
        event.preventDefault();

        const username = document.getElementById("username").value;
        const password = document.getElementById("password").value;

        // You can add your login validation logic here.
        // For a basic example, let's check if the username and password are both "admin".
        if (username === "admin" && password === "admin") {
            alert("Login successful!");
            // You can redirect the user to another page or perform other actions here.
        } else {
            alert("Invalid username or password. Please try again.");
        }
    });
});
