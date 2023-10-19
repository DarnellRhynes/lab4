<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Document</title>
</head>
<body>
  <h1>Volunteer Form</h1>
  <form action="http://bloomingdale.sat.iit.edu/kriedan/lab3formscript.php" method="post">
    <fieldset>
      <legend>My Info</legend>
      <div><label>First Name: <input size="100" type="text" name="first_name_field"></label></div>
      <div><label>Last Name: <input size="100" type="text" name="last_name_field"></label></div>
      <div><label>Phone: <input size="100" type="text" name="phone_field"></label></div>
      <div><label>Email: <input size="100" type="text" name="email_field"></label></div>
      <div>Gender: </div>
      <div>
        <label>Male <input type="radio" name="gender_field" value="male"></label>
        <label>Female <input type="radio" name="gender_field" value="female"></label>
      </div>
      <div>Age: </div>
      <select name="age_field">
        <option>under 20</option>
        <option>over 20</option>
      </select>
    </fieldset>
    <fieldset>
      <legend>My Availability</legend>
      <h3>Days Available:</h3>
      <div>
        <div><label>Sunday <input type="checkbox" name="available_field[]" value="Sunday"></label></div>
        <div><label>Monday <input type="checkbox" name="available_field[]" value="Monday"></label></div>
        <div><label>Tuesday <input type="checkbox" name="available_field[]" value="Tuesday"></label></div>
        <div><label>Wednesday <input type="checkbox" name="available_field[]" value="Wednesday"></label></div>
        <div><label>Thursday <input type="checkbox" name="available_field[]" value="Thursday"></label></div>
        <div><label>Friday <input type="checkbox" name="available_field[]" value="Friday"></label></div>
        <div><label>Saturday <input type="checkbox" name="available_field[]" value="Saturday"></label></div>
        <h3>Comments</h3>
        <textarea name="Comments_field"></textarea>
      </div>
    </fieldset>
    <input type="hidden" name="hidden_field" value="Darnell Rhynes">
    <input type="submit">
  </form>
</body>
</html>
