<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Computer Software Form</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Computer Software Form</h1>
    <form>
        <!-- First Edit Field -->
        <label for="software-name">Software Name:</label><br>
        <input type="text" id="software-name" name="software-name" placeholder="Enter software name"><br><br>

        <!-- Second Edit Field -->
        <label for="developer-name">Developer Name:</label><br>
        <input type="text" id="developer-name" name="developer-name" placeholder="Enter developer name"><br><br>

        <!-- First Check Box -->
        <label>
            <input type="checkbox" id="open-source" name="open-source">
            Is it open source?
        </label><br><br>

        <!-- Second Check Box -->
        <label>
            <input type="checkbox" id="subscription" name="subscription">
            Requires subscription?
        </label><br><br>

        <!-- Buttons -->
        <button type="submit" class="btn save">Save</button><br><br>
        <button type="button" class="btn cancel">Cancel</button>
    </form>
</body>
</html>
/* General styles */
body {
    font-family: Arial, sans-serif;
    margin: 20px;
    text-align: center;
}

/* Title styles */
h1 {
    margin-bottom: 1cm;
    font-size: 2em;
}

/* Form styles */
form {
    display: inline-block;
    text-align: left;
}

/* Edit fields */
input[type="text"] {
    width: 300px;
    padding: 10px;
    background-color: #d0e7ff; /* Blue background */
    border: 1px solid #ccc;
    border-radius: 5px;
    margin-bottom: 1cm; /* Gap between fields */
}

/* Labels */
label {
    font-weight: bold;
}

/* Buttons */
.btn {
    width: 120px;
    padding: 10px;
    color: white;
    background-color: orange;
    border: none;
    border-radius: 5px;
    font-size: 1em;
    cursor: pointer;
}

.btn:hover {
    background-color: #ff9800; /* Slightly darker orange on hover */
}

.save {
    margin-bottom: 1cm; /* Distance between Save and Cancel buttons */
}

