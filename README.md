<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Class Work</title>
    <style>
        .cw2{
            text-align: center;
            color: green;

        }
        .frm{
            border: 5px solid green;
            width: 350px;
            height: 400px;
            margin: auto;
            padding: 20px;
        }
        .center{
            display: block;
            margin-left: auto;
            margin-right: auto;
            width: 5%;
        }
        hr{
            border: 3px solid red;
        }
    </style>
</head>
<body>
    <div>
        <img src="images/efogo.png" class="center">
        
        <h1 class="cw2">Efogo Computer Eduction</h1>
        <p class="cw2">My First Class Work <span style="color:red;">Modified</span></p>


        <form class="frm" action="">
            <label for="fname">First Name</label>
            <input type="text" name="fname" placeholder="Enter Your First Name">
            <br><br>
            <label for="lname">Last Name</label>
            <input type="text" name="lname" placeholder="Enter Your Last Name">
            <br><br>
            
            <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
            <label for="vehicle1"> I am a Man</label><br>
            <input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
            <label for="vehicle2"> I am a Woman</label><br>
            <input type="checkbox" id="vehicle3" name="vehicle3" value="Boat">
            <label for="vehicle3"> Others</label>

            <br><br>

            <input type="radio" name="fig" value="Male">
            <label for="male">Man</label><br>
          
            <input type="radio" name="fig" value="Female">
            <label for="female">Woman</label><br>
          
            <input type="radio" name="fig" value="Others">
            <label for="others">Others</label>

            <br><br>
            <input type="submit" value="Submit">
            <br><br>
            <hr>
            
            <h3 class="cw2">Efogo Computer Eduction</h3>
            <table style="width: 350px; text-align: center; border: 3px solid gray;">
                <tr style="background-color: gray; color: aliceblue;">
                    <th>School</th>
                    <th>Location</th>
                    <th>Date</th>
                    <th>Time</th>
                </tr>
                <tr style="background-color: gray; color: aliceblue;">
                    <td>Efogo Comp Sc.</td>
                    <td>Alatunshe</td>
                    <td>17/05/2022</td>
                    <td>9am</td>
                </tr>
            </table>
            
        </form>
    </div>
    
</body>
</html>
