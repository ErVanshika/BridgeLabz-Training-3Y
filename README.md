                                                                                       # BridgeLabz-Training-3Y
<!DOCTYPE html>
<html lang="en">

<head>
    <title>student Registration Form</title>
</head>

<body></body>


<table border="1" width="80%">
    <tr>
        <th colspan="2">Student registration</th>
    </tr>
    <tr>
        <td>Name:</td>
        <td><input type="text" placeholder="Enter your name"></td>
    </tr>
    <tr>
        <td>Email:</td>
        <td><input type="email" placeholder="Enter your email"></td>
    </tr>
    <tr>
        <td>Phone:</td>
        <td><input type="number" placeholder="Enter your phone number"></td>
    </tr>
    <tr>
        <td>Date:</td>
        <td><input type="date"></td>
    </tr>
    <tr>
        <td>Skill:</td>
        <td><input type="radio" name="skill" value="html"> HTML
            <input type="radio" name="skill" value="css"> CSS
            <input type="radio" name="skill" value="js"> JavaScript</td>
    </tr>
    <tr>
        <td>Gender:</td>
        <td><input type="radio" name="gender" value="male"> Male
            <input type="radio" name="gender" value="female"> Female</td>
    </tr>
    <tr>
        <td>Course:</td>
        <td>
            <select name="course">
                <option value="">--Select Course--</option>
                <option value="B.tech">B.tech</option>
                <option value="bcom">BCOM</option>
                <option value="bca">BCA</option>
                <option value="bba">BBA</option>

            </select>
        </td>
    </tr>
    <tr>
        <td>Address:</td>
        <td>
            <textarea name="address" rows="5" cols="30"></textarea>
        </td>
    </tr>
    <tr>
        <td>upload resume</td>
        <td><input type="file" name="resume"></td>
    </tr>

    <tr>
        <td colspan="2" align="center">
            <input type="submit" value="Register">
            <input type="reset" value="Reset">
        </td>
    </tr>
</table>

</body>

</html>