# ResumeBuilding
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h2>Resume Building</h2>
    <form action="backend-Php"></form>
    <label for="name"></label>
    <div>Name:<input type="text" name="Name" id="name" /></div>
    <br />
    <div>Ph.No:<input type="text" name="MyRole" /></div>
    <br />
    <div>Email:<input type="email" name="" name="MyEmail" /></div>
    <br />
    <br />
    <div>Date:<input type="date" name="MyDate" /></div>
    <br />
    <div>Year of Passout: <input type="year" name="MyYear" /></div>
    <br />
    <div>
      <label for="car"></label>
      Qalification:<select name="collegeName" id="cg">
        <option value="1">Graduation</option>
        <option value="2">Pre-University Education</option>
        <option value="3">High School</option>
      </select>
    </div>
    <br />
    <div>
      Are you Eligible?: <input type="checkbox" name="MyEligibility" checked />
    </div>
    <br />
    <div>
      Write about yourself:<br /><textarea
        name="Mytext"
        cols="30"
        rows="10"
      ></textarea>
    </div>
    <br />
    <div>
       Upload Resume: <input type="file" name="Portfolio" /> 
      </div>
      <div>
        Upload Image:<input type="file" name="Image"/>
      </div>
    <div>
      Gender:Male <input type="radio" name="MyGender" /> Female

      <input type="radio" name="MyGender" /> Other

      <input type="radio" name="MyGender" />
    </div>

    <div>
      <input type="submit" value="submit now" />

      <input type="reset" value="reset now" />
    </div>
  </body>
</html>
