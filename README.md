	<!DOCTYPE html>
<html lang="en">
<head>
    <title>submitted</title>
<title>Application Form</title>
<link rel="stylesheet" href="./form.css">
<div>
<h1> Application Form</h1>
</div>
</head>
<body>
<form action="./formmessage.html">
<fieldset>
<legend>Personal Details:</legend>
<div>
<label for="firstname">First Name:</label>
<input type="text" name="firstname" id="firstname" placeholder="Enter your first name" required>
</div>
<br>
<div>
<label for="email">Email:</label>
<input type="email" name="email" id="email" placeholder="Enter your email id">
</div>
<br>
<div>
<label for="password">Password:</label>
<input type="password" name="password" id="password" placeholder="Enter your Password here" pattern="[A-Z]{1}[a-z]{5}[1-9]{2}" autofocus required >
</div>
<br>
<br>
</div>
<fieldset>
<legend name="language" id="language" >
<option value="Select">Select your skill</option>
<input type="checkbox"="C">C</option></br>
<input type="checkbox"="C++">C++</option></br>
<input type="checkbox"="Java">Java</option></br>
<input type="checkbox"="Python">Python</option></br>
<input type="checkbox"="C#">C#</option></br>
</fieldset>
</div>
<br>
<br>
<fieldset>
<legend for="Gender">Gender:</legend>
<input type="radio" name="male">Male <br>
<input type="radio" name="female">Female <br>
<input type="radio" name="other">Other <br>
</fieldset>
<br>
<br>
<fieldset>
<legend for="telephone">Phone Number:</legend>
<input type="tel" name="telephone" id="telephone" placeholder="add your mobile number" pattern="[0-9]{3}[0-9]{3}[0-9]{4}">
<br>
<div>
<label for="address">Address:</label><br>
<textarea name="address" id="address" placeholder="add your address" cols="30" rows="5"></textarea>
</div>
<br>
</fieldset>
<br>
<button>Submit</button>
<br>
</form>
</body>
</html>
