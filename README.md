ex8
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Web Page</title>
</head>
<body>

  <h1>Welcome to My Web Page</h1>

  <!-- Creating a table -->
  <table border="1">
    <caption>Sample Table</caption>
    <tr>
      <th>Name</th>
      <th>Age</th>
    </tr>
    <tr>
      <td>John</td>
      <td>30</td>
    </tr>
    <tr>
      <td>Jane</td>
      <td>25</td>
    </tr>
  </table>

  <!-- Adding an image -->
  <img src="https://via.placeholder.com/150" alt="Placeholder Image">

  <!-- Creating a list -->
  <h2>My Favorite Things</h2>
  <ul>
    <li>Books</li>
    <li>Music</li>
    <li>Traveling</li>
  </ul>

  <!-- Creating a frame -->
  <h2>External Website Frame</h2>
  <iframe src="https://www.example.com" width="600" height="400"></iframe>

  <!-- Adding a hyperlink -->
  <h2>Useful Links</h2>
  <ul>
    <li><a href="https://www.example.com">Example Website</a></li>
    <li><a href="https://www.wikipedia.org">Wikipedia</a></li>
    <li><a href="https://www.github.com">GitHub</a></li>
  </ul>

</body>
</html>
ex81
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Web Page</title>
</head>
<body>

  <h1>Welcome to My Web Page</h1>

  <!-- Creating a table -->
  <table border="1">
    <caption>Sample Table</caption>
    <tr>
      <th>Name</th>
      <th>Age</th>
    </tr>
    <tr>
      <td>John</td>
      <td>30</td>
    </tr>
    <tr>
      <td>Jane</td>
      <td>25</td>
    </tr>
  </table>

  <!-- Adding an image -->
  <img src="https://via.placeholder.com/150" alt="Placeholder Image">

  <!-- Creating a list -->
  <h2>My Favorite Things</h2>
  <ul>
    <li>Books</li>
    <li>Music</li>
    <li>Traveling</li>
  </ul>

  <!-- Creating a frame -->
  <h2>External Website Frame</h2>
  <iframe src="https://www.example.com" width="600" height="400"></iframe>

  <!-- Adding a hyperlink -->
  <h2>Useful Links</h2>
  <ul>
    <li><a href="https://www.example.com">Example Website</a></li>
    <li><a href="https://www.wikipedia.org">Wikipedia</a></li>
    <li><a href="https://www.github.com">GitHub</a></li>
  </ul>

</body>
</html>
ex82 ok 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Panimalar Engineering College</title>
<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-image: url('panimalar_engineering_college_background.jpg');
        background-size: cover;
        background-position: center;
    }
    header {
        background-color: rgba(0, 0, 0, 0.5);
        color: #fff;
        padding: 20px;
        text-align: center;
    }
    nav {
        float: left;
        width: 20%;
        background: rgba(255, 255, 255, 0.8);
        padding: 20px;
    }
    nav ul {
        list-style-type: none;
        padding: 0;
    }
    nav ul li {
        padding: 10px 0;
    }
    section {
        float: left;
        width: 80%;
        padding: 20px;
        background-color: rgba(255, 255, 255, 0.8);
    }
    .frame-container {
        width: 100%;
        height: 300px;
        overflow: auto;
    }
    footer {
        background-color: rgba(0, 0, 0, 0.5);
        color: #fff;
        text-align: center;
        padding: 20px;
        clear: both;
    }
</style>
</head>
<body>

<header>
    <h1>Welcome to Panimalar Engineering College</h1>
</header>

<nav>
    <h2>Courses Offered</h2>
    <ul>
        <li><a href="#" onclick="displayCourse('cse')">Computer Science and Engineering</a></li>
        <li><a href="#" onclick="displayCourse('ece')">Electronics and Communication Engineering</a></li>
        <li><a href="#" onclick="displayCourse('mech')">Mechanical Engineering</a></li>
        <li><a href="#" onclick="displayCourse('civil')">Civil Engineering</a></li>
        <li><a href="#" onclick="displayCourse('it')">Information Technology</a></li>
    </ul>
</nav>

<section>
    <div class="frame-container">
        <div id="courseObjective"></div>
        <div id="courseOutcome"></div>
    </div>
</section>

<footer>
    <p>&copy; 2024 Panimalar Engineering College. All rights reserved.</p>
    <p><a href="https://www.panimalar.ac.in/">Visit our website</a></p>
</footer>

<script>
    var courseData = {
        cse: {
            objective: "To provide students with a solid foundation in computer science principles and practical skills.",
            outcome: "Graduates will be equipped to design and develop software systems, analyze algorithms, and solve complex computing problems."
        },
        ece: {
            objective: "To educate students in the field of electronics and communication engineering.",
            outcome: "Graduates will have the skills to design and implement electronic circuits, communication systems, and signal processing techniques."
        },
        mech: {
            objective: "To impart knowledge in mechanical engineering principles and applications.",
            outcome: "Graduates will be capable of designing mechanical systems, analyzing thermal processes, and applying engineering principles to solve real-world problems."
        },
        civil: {
            objective: "To educate students in the planning, design, and construction of civil engineering structures.",
            outcome: "Graduates will possess the skills to design and manage infrastructure projects, analyze structural systems, and apply sustainable engineering practices."
        },
        it: {
            objective: "To provide students with a strong foundation in information technology concepts and technologies.",
            outcome: "Graduates will be prepared to develop and manage IT systems, implement network solutions, and apply emerging technologies in various domains."
        }
    };

    function displayCourse(course) {
        document.getElementById("courseObjective").innerHTML = "<h3>Objective:</h3><p>" + courseData[course].objective + "</p>";
        document.getElementById("courseOutcome").innerHTML = "<h3>Outcome:</h3><p>" + courseData[course].outcome + "</p>";
    }
</script>

</body>
</html>
