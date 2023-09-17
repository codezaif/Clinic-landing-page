# Clinic-landing-page
this is simple landing page for any Clinic and anyone can use this code for their purpose by modifying i will appreciate this if anyone use my code
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MH Clinic</title>
    
    <style>
        /* css reset */
        * {
            box-sizing: border-box;
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        }

        body {
            background-image: url(psy.jpg);
            height: 600px;
            background-repeat: no-repeat;
            background-size: cover;
            color: black;
            


        }

        .container {
            border: 2px solid black;
            border-radius: 50px;
            width: 55%;
            display: block;
            margin: 2px auto;

        }

        h3 {



            display: inline-block;
            width: 53%;
            margin: 59px 194px;
            font-size: 25px;
            font-weight: bolder;
            text-align: center;
            color: black;
        }

        .left {

            display: inline-block;
            position: absolute;
            top: -36px;
            left: 0px;

        }

        .left img {


            width: 160px;


        }

        .mid {

            display: block;
            width: 50%;
            margin: 22px auto;
        }

        .right {

            display: inline-block;
            position: absolute;
            right: 16px;
            top: 6px;
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
            width: 100px;
            background-color: gray;
            font-weight: bolder;
            border-radius: 200px;



        }

        .right:hover {
            background-color: rgb(0, 0, 0);
            color: white;
        }

        .navbar {
            display: inline-block;
        }

        .navbar li {
            display: inline-block;
            font-size: 15px;
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
            font-weight: bold;
        }

        .navbar li a {
            color: black;
            text-decoration: none;
            padding: 6px 10px;
            margin: 20px 30px;
            font-weight: bolder;
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
            font-size: 17px;
        }

        .navbar li a:hover {
            background-color: rgb(0, 0, 0);
            border: 2px solid white;
            border-radius: 20%;
            color: rgb(255, 255, 255);
        }

        .formgroup {
            text-align: center;
            display: block;
            width: 450px;
            padding: 11px;
            border: 2px solid black;
            border-radius: 14px;
            margin: 3px 110px;
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
            font-size: 15px;

        }

        .formgroup input {
            border: 2px solid black;
            border-radius: 8px;
            background-color: transparent;
        }

        .btn {
            margin: 0px 10px;
            background-color: white;
            color: black;
            padding: 4px 4px;
            border: 2px solid gray;
            border-radius: 10px;
            cursor: pointer;
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
            font-size: 14px;
            font-weight: bold;
            display: block;
            width: 20%;
            margin: 2px 280px;
        }
        .btn:hover{
            background-color: black;
            color: white;
        }
        .textarea{
            border-radius: 10px;
        }
        
        
    </style>

</head>

<body>
    <header class="header">
        <div class="left">
            <!-- left box for navabr -->
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <img src="mh.png" alt="logo">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

        </div>
        <div class="mid">
            <!-- div for navbar -->
            <div class="navbar">
                <ul>
                    <li><a href="#">Book Your Appointment</a></li>
                    <li><a href="#">Contact Us</a></li>
                    <li><a href="#">About Us</a></li>
                </ul>
            </div>
        </div>
        <div class="right">
            <button class="right">Login</button>
        </div>
    </header>
    <div class="container">
        <h3>What brings you in today? </h3>
        <form action="noaction.php">
            <div class="formgroup">
                <strong>Name</strong>
                <input type="text" name="" placeholder="">
            </div>
        </form>
        <div class="formgroup">
            <strong>Age</strong>
            <input type="text" name="" placeholder="">
        </div>
        </form>
        <div class="formgroup">
            <strong>Gender</strong>
            <input type="radio" name="gender">Male
            <input type="radio" name="gender">Female
            <input type="radio" name="gender">Others
        </div>
        </form>
        <div class="formgroup">
            <strong
                style="font-weight: bolder; font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif; font-size: 20px;">Your
                confession</strong><br>
            <textarea name="Describe Your Problem" cols="30" rows="5" class="textarea"></textarea>
        </div><br>
        <button class="btn">SUBMIT</button>
        </form>
    </div>
    
</body>

</html>
