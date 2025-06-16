<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>student entry</title>
    <style>
        form{
             column-count: auto;
        }
    </style>
</head>
<body>
    <center>
    <h1>Student registeration</h1>
    <form action="/" method="post">
    <table border="1" cellpading="10" >
        <tr>
            <td>
                <label for="">Full Name:</label>
                <input type="text" required placeholder="Enter your Full Name">
            </td>
        </tr>
        <tr>
            <td>
                <label for="">Email Address:</label>
                <input type="email" required placeholder="Enter your Email">
            </td>
        </tr>
        <tr>
            <td>
                <label for=""></label>
            </td>
        </tr>
        <tr>
            <td>
                <label for="">Phone Number:</label>
                <input type="tel" required pattern="[0-9]{10}" placeholder="Enter your Phone Number">
            </td>
        </tr>
        <tr>
            <td>
                <label for="">Date Of Birth:</label>
                <input type="date" required placeholder="Enter your Date of Birth" min="2000-01-01" max="2025-12-31">
            </td>
        </tr>
        <tr>
            <td>
                <label for="">Gender:</label>
                <input type="radio" checked name="Gender:">MALE
                <input type="radio" checked name="Gender:">FEMALE
                <input type="radio" checked name="Gender:">OTHER
            </td>
        </tr>
        <tr>
            <td>
                <label for="">COURSE:</label>
                
                <select name="" id="">
                    <option value="">C</option>
                    <option value="">PYTHON</option>
                    <option value="">HTML</option>
                </select>
                
            </td>
        </tr>
        <tr>
            <td>
                <label for="">Prefered Timing</label>
                <input type="checkbox" name="morning">Morning
                <input type="checkbox" name="afternoon">Afternoon
                <input type="checkbox" name="evening">Evening
            </td>
        </tr>
        <tr>
            <td>
                <label for="">Comment Box</label>
                <input type="textarea" rows="4" placeholder="Enter Your Comment Here">
            </td>
        </tr>
        <tr>
            <td>
                <label for=""></label>
            </td>
        </tr>
        <tr>
            <td>
                <center>
                <button type="submit">REGISTER</button>
                <button type="reset">RESET</button>
                </center>
            </td>
        </tr>

    </table>
    </form>
    </center>
</body>
</html>
