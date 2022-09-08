<!DOCTYPE html>
<html>
    <head>
        <title>Learning html(Membership) form)</title>
    </head>
    <hr>
    <body>
     <h2><p align="center">SITA RAM MEMBERSHIP FORM</p></h2>
     <hr>
      <h4><p align="Left">PERSONAL INFORMATION:</p></h4>
     
     <Form>
      <label for="First name:">First name:</label>
      <input type="text" Id="First name" name="First name" placeholder="Type in block letters" required>
      <br><br>
      <label for="Last name:">Last name:</label>
      <input type="text" Id="Last name" name="Last name" placeholder="Type in block letters" required>
      <br><br>
      <label for="Date:">D.o.b:</label>
      <input type="Date" Id="Date" name="Date" placeholder="DD/MM/YYYY" required> 
      <br>
      <p>Select your Gender:</p>
      <input type="radio" name="Gender" value="Female" Id="Option-1">
      <label for="Option-1">Female</label>
      <br>
      <input type="radio" name="Gender" value="Male" Id="Option-2">
      <label for="Option-2">Male</label>
      <br>
      <input type="radio" name="Gender" value="Hermaphrodite" Id="Option-3">
      <label for="Option-1">Hermaphrodite</label>
      <br><br>
        <label for="Religion">Religion: </label>
      <select name="Religion" Id="Religion">
          <option value="q1">Select</option>
           <option value="q2">Christianity</option>
          <option value="q3">Muslim</option>
         <option value="q4">Others</option>
      </select>
      <hr>
      
      <h4><p align="Left">CONTACT INFORMATION:</p></h4>
      
      <label for="email">Enter email:</label>
      <input type="email" name="email" Id="email" placeholder="Type in active email address" required>
      <br><br>
      <label for="number">Tel:</label>
      <input type="number" name="number" Id="number" placeholder="+91" required>
          <p>Address:</p>
      <input type="text" name="Country" Id="Country" placeholder="Country" required>
      <input type="text" name="State" Id="State" placeholder="State" required> 
       <input type="text" name="City" Id="City" placeholder="City" required>
        <input type="text" name="Street address" Id="Street address" placeholder="Street address" required>
        <hr>
      <h4><p align="Left">Question:</p></h4>
      <p>Why do you want to be a member?</p>
      <textarea name="Comment" Id="Comment" cols="30" row="10" placeholder="Not less than 100 words..."></textarea>
      <hr>
      <p><em>Confirmation text will be sent to your email when you submit below</em></p>
      👉<input type="SUBMIT" Value=SUBMIT!>👈
     </Form>
    </body>
</html>
