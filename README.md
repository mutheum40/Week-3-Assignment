# Week-3-Assignment
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Student Registration Form</title>
  <style>
    label {
      display: block;
      margin-bottom: 5px;
    }
    input, select {
      width: 100%;
      padding: 8px;
      margin-bottom: 10px;
      box-sizing: border-box;
    }
    button {
      padding: 10px 20px;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    button:hover {
      background-color: #45a049;
    }
    .btn-group {
      margin-top: 20px;
    }
    .btn-group button {
      margin-right: 10px;
    }
  </style>
</head>
<body>

<form action="#" method="POST">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" required>
  
  <label for="dob">Date of Birth:</label>
  <input type="date" id="dob" name="dob" required>
  
  <label for="gender">Gender:</label>
  <select id="gender" name="gender" required>
    <option value="">Select Gender</option>
    <option value="male">Male</option>
    <option value="female">Female</option>
    <option value="other">Other</option>
  </select>
  
  <label for="address">Address:</label>
  <input type="text" id="address" name="address" required>
  
  <label for="telephone">Telephone:</label>
  <input type="tel" id="telephone" name="telephone" required>
  
  <label for="email">Email Address:</label>
  <input type="email" id="email" name="email" required>
  
  <label for="course">Course:</label>
  <input type="text" id="course" name="course" required>
  
  <div class="btn-group">
    <button type="submit" name="submit">Register</button>
    <button type="reset" name="reset">Cancel</button>
  </div>
</form>

</body>
</html>
