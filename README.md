<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TUTOR MEJAVA LEARNING PLATFORMS</title>
</head>
<body>
    <h1><B>TUTOR ME JAVA LEARNING PLATFORM </B></h1>
    <P>In this website u can gather information about different learning JAVA website from begginer level.
        This website can be applicable for all new learner. <br>
        <h2>What is JAVA?</h2>
        <p>Java is a widely-used programming language for coding web applications. It has been a popular choice among developers for over two decades, with millions of Java applications in use today. Java is a multi-platform, object-oriented, and network-centric language that can be used as a platform in itself. It is a fast, secure, reliable programming language for coding everything from mobile apps and enterprise software to big data applications and server-side technologies.

            <br>It’s used by businesses worldwide to power mobile apps, software, and websites — almost 92.8% of all websites.</p>
        <h2>TOP JAVA WEBSITES</h2>
        <ol><li>Guru99</li>
        <li>Javapoint</li>
    <li>GUVI</li>
<li>W3school</li>
<h3>Guru99</h3>
<p>Javapoint is an online education company that creates and delivers courses, career and skill paths focusing on programming languages. It is a platform that is ideal for beginners and someone who is looking to learn a new skill or gain experience for a new career. <br>The basic membership is free and features a variety of courses that students can take without any financial obligation</p>
  To Know more about us <a href="https://www.javatpoint.com/java-tutorial"><b>visit us</b></a>  
   <h3>Javapoint</h3>
   <P>Guru99 is a global online learning platform that offers anyone, anywhere, access to online courses and degrees from leading universities and companies.</P>
   To know more about us <a href="https://www.guru99.com/java-platform.html"><b>visit us</b></a>
   <H3>Guru99</H3>
   <p>GUVI is an online learning community with thousands of classes for creative and curious people, on topics including illustration, design, photography, video, freelancing, and more. On Skillshare, members come together to find inspiration and take the next step in their creative journey.</p>
   To know more about us <a href="https://www.guvi.in/courses/programming/java-programming/"> visit us</a>
<h3>W3SCHOOLS</h3>
<p>W3Schools is a school for web developers, covering all the aspects of web development.W3Schools was created in 1998, and derives its name from the World Wide Web (WWW) but is not affiliated with the W3C class. <br><br>
To know more about us <a href="https://www.w3schools.com/java/java_intro.asp">visit us</a>
</p>
</P>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Three-Column Layout</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        footer {
            background-color: #333;
            color: #Bule;
            padding: 10px;
            text-align: center;
            position: absolute;
            bottom: 0;
            width: 100%;
        }

        .container {
            display: flex;
            justify-content: space-between;
            max-width: 1200px;
            margin: 20px auto;
        }

        .column {
            flex: 1;
            padding: 20px;
            background-color: #f2f2f2;
            border: 1px solid #ccc;
            box-sizing: border-box;
        }

        /* Adjust column width for larger screens */
        @media screen and (min-width: 768px) {
            .container {
                flex-wrap: wrap;
            }

            .column {
                flex-basis: 30%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Three-Column Layout</h1>
    </header>

    <div class="container">
        <div class="column">
            <h2>Column 1</h2>
            <p>Concepts of object-oriented programming concepts, which include encapsulation, inheritance, abstraction and polymorphism.
            Good understanding of various data types with a few java language classes like System, String-Math and much more.</p>
        </div>
        <div class="column">
            <h2>Column 2</h2>
            <p>Start reading books written by Java professionals and programmers giving a proper insight into the process of coding. Java learning steps might be crucial and critical, hence reading some great books written by experts, must be one of the basic things for you.</p>
        </div>
        <div class="column">
            <h2>Column 3</h2>
            <p>Try some logic exercises like.Deciding a factorial of a number.Finding all prime numbers between 1 to 1000.Print the number in word.Try file input/output.Read a file and display its content right on the console etc...</p>
        </div>
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
    <style>
        /* Basic form styling (you can customize this further) */
        form {
            max-width: 400px;
            margin: 0 auto;
        }

        label, input, select {
            display: block;
            margin-bottom: 10px;
        }

        button {
            margin-top: 10px;
        }

        .error {
            color: red;
        }
    </style>
</head>
<body>
    <form action="" method="get" name="enquiry">
	I’m Interested in this Program

</form>
    <form id="registrationForm" onsubmit="return validateForm()">
        
    </form> <label>First Name: <input type="text"></label>
        <label for="lname">Last Name:</label>
        <input type="text" id="lname">
        

        <label for="email">Email:</label>
        <input type="email" id="email" required>
        
        <label for="phone">Phone Number:</label>
        <input type="tel" id="phone" required pattern="[0-9]{10}" placeholder="Enter a 10-digit phone number">
        
        <label for="qualification">Educational Qualification:</label>
        <input type="text" id="qualification" required>
        <label for="passingYear">Year of Passed Out:</label>
        <input type="number" id="passingYear" required min="2019" max= "2026">
        
        <label>Age: <input type="text" size="3"> </label>
        
        
        <label for="password">Password:</label>
        <input type="password" id="password" required>

        <label for="confirmPassword">Confirm Password:</label>
        <input type="password" id="confirmPassword" required>

        <label>Gender:</label>
        <input type="radio" name="gender" value="male" required>Male
        <input type="radio" name="gender" value="female" required>Female

        
        
        <label>Interests:</label>
        <input type="checkbox" name="interests" value="sports">Sports
        <input type="checkbox" name="interests" value="music">Music
        <input type="checkbox" name="interests" value="reading">

        <label for="country">Country:</label>
        <select id="country" required>
            <option value="">Select a country</option>
            <option value="usa">USA</option>
            <option value="canada">Canada</option>
            <option value="uk">UK</option>
            <option value="uk">INDIA</option>
            
            <!-- Add more countries as needed -->
        </select>
         <label for="Select City">City:</label>
        <select id="city" required>
            <option value="">Select a city</option>
            <option value="Salem">Salem</option></option>
            <option value="Chennai">Chennai</option></option>
            <option value="Mayiladuthurai">Mayiladuthurai</option>
            <option value="Coimbatore">Coimbatore</option>
        

        <button type="submit">Register</button>
        <label><input type="checkbox" checked>: I Agree</label>
        </form>


    <script>
        function validateForm() {
            // Basic validation for password match
            var password = document.getElementById("password").value;
            var confirmPassword = document.getElementById("confirmPassword").value;
            if (password !== confirmPassword) {
                alert("Passwords do not match!");
                return false;
            }

            // You can add more custom validations here based on your requirements.

            return true; // If all validations pass, the form will be submitted.
        }
<label><input type="checkbox" checked>: I Agree
    </script>
</body>
</html>
