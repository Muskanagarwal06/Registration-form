# Registration-Form
Registration form created using HTML.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <main>
        <h2><u>Registration Form</u></h2>
        <form action="/action.php">
        <input type="Text" placeholder="Type Your Name">
        <input type='Text' placeholder="Type Username">
        <input type ="Password" placeholder="Password">
        <h3>Select your Class:</h3>
        <label for="101">
            <input type="Radio" value="Class 10th" name="class" id="101">Class X
        </label>
        <br>
        <label for="102">
        <input type="Radio" value="Class 11th" name="class" id="102">Class XI
        </label>
        <br>
        <label for="103">
        <input type="Radio" value="Class 12th" name="class" id="103">Class XII
        </label>
        <br>
        <h3>Select your subject/subjects:</h3>
        <label for="Math">
            <input type="checkbox" value="Math" name="Subject" id="'101">Math
        </label>
        <br>
        <label for="Physics">
            <input type="checkbox" value="Physics" name="Subject" id="102">Physics
        </label>
        <br>
        <label for="ComputerScience">
            <input type="checkbox" value="ComputerScience" name="Subject" id="103">ComputerScience
        </label>
        <br>
        <h3>Select your city:</h3>
        <select name="City">
            <option value="Delhi">Delhi</option>
            <option value="Bangalore">Bangalore</option>
            <option value="Kolkata">Kolkata</option>
            <option value="Bombay">Bombay</option>
            <option value="Chandigarh">Chandigarh</option>
        </select>
        <br>
        <h4>Feedback:</h4>
        <textarea name="Feedback" id="1110" placeholder="Please give your Feedback here" rows=5 ></textarea>
        <br>
        <br>
        <input type="submit" value="Submit">
        <br>
        </form>
    </main>
</body>
</html>