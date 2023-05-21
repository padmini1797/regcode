<!DOCTYPE html>
<html lang="en">
<head>
    <title>Registration page</title>
</head>
<body>
    <div style="margin:auto;border:2px solid orange;padding:10px;height:400px;width:400px;">
    <h1 align="center" style="color:orange">Book a Call</h1>
    <p align="center">Book a call slot and our representative will call you within 1hr of selected time.</p>
    <hr>
    <form onsubmit="onbook(event)">
    <label for id="name">Name:</label><br>
    <input type="text" id="name" name="name"size=50><br>
    <label for id="mail">Email:</label><br>
    <input type="email" id="mail" name="mail" size=50><br>
    <label for id="phone">Phone:</label><br>
    <input type="tel" id="phone" name="phone" size=50><br>
    <label for id="calltime">Time for call:</label><br>
    <input type="date" id="calltime" name="call time">
    <input type="time" id="tim" name="tim"><br>
    <input type="submit" 
    style="background-color:orange;color:white;font-family:monospace;text-align:center;height:50px;width:389px"
    value="GET A CALL">
    </form>
    </div>
</body>
</html>
