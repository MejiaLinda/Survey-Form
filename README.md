# Survey-Form
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>Survey Form</title>
    <link rel="stylesheet" type="text/css" href="styles.css" />
    <style>
      #title, {
        text-align: center;
      }
      #description{
       color: green;
      }
      #name{
       color: green;
      }
      
      #survey-form{
        background-color: #1b1b32;
        color: white;
      }
      </style>
  </head>
  <body>
    <h1 id="title">Survey Form</h1>
    <p id="description">Please fill out this form with the required information</p>
    <form id="survey-form" class="survey-form">
      <fieldset>
        <label id="name-label">Name:<input id="name" name="name-label" type="text" placeholder="Introduce your first and last name" required /></label>
        <label id="email-label">Email <input id="email" name="email-label" type="email" placeholder="Introduce a valid email address"required/></label>
        <label id="number-label">Number: <input id="number" name="number-label" type="number" min="001" max="100" placeholder="Introduce a number between 001-100" required /></label>
      </fieldset>
      <fieldset>
        <label for="dropdown">What is your car brand?
          <select id="dropdown" name="dropdown">
            <option value="">(select one)</option>
            <option value="1">Toyota</option>
            <option value="2">Nissan</option>
            <option value="3">Ford</option>
            <option value="4">Hyundai</option>
            <option value="4">Mitsubishi</option>
            <option value="5">Other</option>
          </select> 
          </label>
          <fieldset>Type of car body style:
        <label for="sedan"><input id="sedan" type="radio" name="sedan" class="inline" value="sedan" /> Sedan</label>
        <label for="suv"><input id="suv" type="radio" name="suv" class="inline" value="suv" /> SUV</label>
         <label for="other" > <input id="other" type="radio" name="other" class="inline" value="other" /> Other</label>
        </fieldset>
        <fieldset>Your favorite type of car body style:
        <label for="sedan"><input id="sedan" type="radio" name="sedan" class="inline" value="sedan" /> Sedan</label>
        <label for="suv"><input id="suv" type="radio" name="suv" class="inline" value="suv" /> SUV</label>
         <label for="other" > <input id="other" type="radio" name="other" class="inline" value="other" /> Other</label>
        </fieldset>
 <filedset>Which Engine should I choose?
        <label for="diesel" name="diesel">
          <input id="diesel" type="checkbox" value="diesel"  name="diesel" class="inline" /> Diesel
          <label for="gasoline" name="gasoline">
          <input id="gasoline" type="checkbox"  name="gasoline" class="inline" value="gasoline" /> Gasoline
        </label>
    
      </fieldset>



       <label for="bio">Additional Comments:
          <textarea id="bio" name="bio" rows="3" cols="30" placeholder="How can we improve..."></textarea>
        </label>
      </fieldset>
      <input id="submit" type="submit" value="Submit" />
    </form>
  </body>
</html>
