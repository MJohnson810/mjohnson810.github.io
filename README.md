<!DOCTYPE html>
<html>
<head>
    <title>A Cool Form</title>
    <link href="silver_city.css" rel=stylesheet type="text/css">
</head>
<body bgcolor="#DCDCDC">
    <div>
    <h1>Silver City</h1>
    <p>Silver City serves as the shopping desitination and work location for many residents in outlying communities. With it's old time western village a steam engine ride through an old silver mine, and a brand new water park this city also serves as a popular tourist attraction. <br><br>
    Please complete this short survey below to help our city better serve the residents and visitors in the downtown area.</p>
    </div>
    <form name="formtest" method="post" action="https://elearn.usu.edu/courses/itls-5265/forms/form_results.php">
        <!-- Put your form code here. -->
    <div>
    <h4 class="colored_bg">The primary reason you are interested in visiting Silver City is:</h4>
        <select>
        <option value="select one">Select One</option>
        <option value="resident">I am a resident of Silver City</option>
        <option value="work">I work in Silver City</option>
        <option value="visit">I visit Silver City to shop or visit businesses</option>
        <option value="tourism">Toursit-Vacation</option>
        <option value="other">Other</option>
        </select>
    </div>
    <div>
    <h4>Current Zip Code:</h4>
        Zip Code:<input type="text" name="zip code" maxlength=10px><br>
    </div>
    <div>
    <h4>How often do you visit Silver City?</h4>
        <input type="radio" name="resident"> I live here<br>
        <input type="radio" name="several times a week"> serveral times a week<br>
        <input type="radio" name="several times a month"> several times a month<br>
        <input type="radio" name="serveral times a year"> several times a year<br>
        <input type="radio" name="once a year"> once a year or less<br>
        <input type="radio" name="never"> I never visit Silver City<br>
    </div>
    <div>
    <h4>What would make downtown Silver City more attractive to visit? (check all that apply)</h4>
        <input type="checkbox" name="attraction" value="restaurants"> more restaurants<br>
        <input type="checkbox" name="attraction" value="stores"> more specialty stores<br>
        <input type="checkbox" name="attraction" value="shops"> more tourist type shops<br>
        <input type="checkbox" name="attraction" value="businesses"> more professional businesses<br>
        <input type="checkbox" name="attraction" value="parking"> additional parking<br>
        <input type="checkbox" name="attraction" value="buses"> a bus route from nearby hotels or popular tourist spots<br>
        <input type="checkbox" name="attraction" value="facelift"> give the place a facelift<br>
        <input type="checkbox" name="attraction" value="events"> concerts and events held downtown<br>
        <input type="checkbox" name="attraction" value="locals"> fewer tourists, and more places for locals<br>
    </div>
    <div>
    <h4>Additional comments or suggestions:</h4>
       <textarea rows="6" cols="100"></textarea>
    </div>
    <div>
    <h4>Enter your email address below to receive occasional information on what is happening in downtown Silver City</h4>
        Email Address:<input type="email" name="email">
    </div>
    <div>
    <br>
    <input type="submit">
    </div>
    </form>
</body>
</html>
