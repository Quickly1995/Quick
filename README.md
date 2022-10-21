<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
<form>

    <h1>Sign up</h1>
    
    <fieldset>
     <strong>Student Name</strong><br><br>
     <input type="text" id="fname" placeholder="First name:" name="fname">&nbsp;&nbsp;&nbsp;&nbsp;
     <input type="text" id="fname" placeholder="Middle name:" name="fname">&nbsp;&nbsp;&nbsp;&nbsp;
     <input type="text" id="lname" placeholder="Last name:" name="lname"><br><br>
     
     <label>Date of Birth</label><br>
      <select id="months" name="months">
       <option></option>
       <option value="January">January</option>
       <option value="February">February</option>
       <option value="March">March</option>
     </select>
     
     <select id="days" name="days">
       <option></option>
       <option value="Sat">Sat</option>
       <option value="Sun">Sun</option>
       <option value="Mon">Mon</option>
     </select>
     
     <select id="years" name="years">
       <option></option>
       <option value="1995">1995</option>
       <option value="1996">1996</option>
       <option value="1997">1997</option>
     </select><br><br>
     
     <label>Gender</label><br>
      <select id="Gender" name="Gender">
       <option></option>
       <option value="Male">Male</option>
       <option value="female">female</option>
     </select>
     
     <br><br>
     <label for="Phone">Phone:</label><br>
     <input type="text" id="text" placeholder="type your phone number:" name="email"><br><br>
     
     <label for="email">Email:</label><br>
     <input type="email" id="email" placeholder="type your email:" name="email"><br><br>
     
       
     <label for="password">Password:</label><br>
     <input type="password" id="password" placeholder="Password:" name="email"><br><br>
     
   
     
     <input type="submit" value="Submit">
    </fieldset>
   </form>
   
   <br>
   
   <h1>Log in</h1>
   <form>
    <fieldset>
    
     <label>Username:</label><br>
     <input type="text" id="fname" placeholder="First name:" name="fname"><br><br>
       
     <label for="password">Password:</label><br>
     <input type="password" id="password" placeholder="Password:" name="email"><br><br>
     
     
    
    <input type="submit" value="send">
    <input type="submit" value="Rest"><br><br>
   
     <input type="submit" value="Submit">
    </fieldset>
   </form>
</body>
</html>
