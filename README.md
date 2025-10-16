# practical-7-b-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dialogue Boxes in JavaScript</title>
</head>
<body>
    <h1>Dialogue Box Examples</h1>

    <button onclick="showAlert()">Show Alert</button>
    <button onclick="showConfirm()">Show Confirm</button>
    <button onclick="showPrompt()">Show Prompt</button>

    <script>
        // Function to show an alert box
        function showAlert() {
            alert("This is an alert box!");
        }

        // Function to show a confirm box
        function showConfirm() {
            const userConfirmed = confirm("Do you want to continue?");
            if (userConfirmed) {
                alert("You clicked OK!");
            } else {
                alert("You clicked Cancel!");
            }
        }

        // Function to show a prompt box
        function showPrompt() {
            const userInput = prompt("Please enter your name:");
            if (userInput) {
                alert("Hello, " + userInput + "!");
            } else {
                alert("You didn't enter anything.");
            }
        }
    </script>
</body>
</html>
