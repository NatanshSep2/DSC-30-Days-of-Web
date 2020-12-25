
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>programming</title>
</head>
<style>
    body {
        color: rgb(44, 43, 43);
        margin: 0px;
        padding: 0px;
        background-image: url('img/nanu10.jpg');
        /* height: 4544px; */
    }
</style>

<body>
    <h2>30 Days of Web Development | Developer Student Clubs | India</h2>
    <form action="backend.php">
        <p>
            30 Days of Web Development will provide you with an opportunity <br>
            to kick start your journey in web development <br>
            and get hands-on experience with <br>
            HTML, CSS, JS,
            Bootstrap, and <br>
            some basics of back-end.
        </p>
        <p>
            Platform where this course being started : <br>
        <ul>
            <li type="square">
                <a href="https://skillenza.com/challenge/30daysofwebdev" target="_blank">skillenza</a><br>
            </li>
        </ul>

        </p>
        <h3>contact info</h3>

        <label for="name"> Name</label>
        <div>
            <input type="text" name="myName" id="name">
        </div>

        <!-- ======================================================================== -->
        <br>

        <label for="phnumber"> Ph.number</label>
        <div>
            <input type="number" name="ph.number" id="phnumber">
        </div>

        <!-- ========================================================================= -->

        <br>
        <label for="email"> Email</label>
        <div>
            <input type="email" name="email" id="email">
        </div>

        <!-- ========================================================================== -->

        <br>
        <label for="date"> Date of birth</label>
        <div>
            <input type="date" name="date" id="date">
        </div>

        <!-- ===========================================================================-->

        <br>
        <div>
            Gender: Male <input type="radio" name="myGender"> Female <input type="radio" name="myGender"> Other <input
                type="radio" name="myGender">
        </div>

        <!-- ========================================================================== -->

        <br>
        <div>
            <!-- "textarea is for write long leters" -->
            <label for="self">write about yourself </label>
            <br><textarea name="self" id="self" cols="30" rows="10"></textarea>
        </div>

        <!-- =========================================================================== -->

        <br>
        <!-- used for choice -->
        <div>
            <label for="Car">Car</label>
            <select name="myCar" id="Car">
                <option value="ind">Indiaca</option>
                <option value="mr" selected>Marsadies</option>
                <option value="bmw">BMW</option>
            </select>
        </div>

        <!-- ============================================================================ -->

        <br>

        <div>
            Reset: <input type="reset">
        </div>
        <br>
        <input type="submit" value="Submit Now">
    </form>
    <p>For any query contact us on Email</p>
    <a href="https://abc@gmail.com" target="_blank">contact us</a>
</body>

</html>
