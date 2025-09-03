<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mengting Han Lab</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }

    /* Header / Banner */
    .header {
      background-color: skyblue;
      padding: 20px;
      text-align: center;
      color: white;
      font-size: 32px;
      font-weight: bold;
    }

    /* Navigation Bar */
    .navbar {
      overflow: hidden;
      background-color: #333;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }

    .navbar a,
    .dropdown .dropbtn {
      color: white;
      text-align: center;
      padding: 14px 20px;
      text-decoration: none;
      background-color: inherit;
      border: none;
      font-size: 16px;
      cursor: pointer;
    }

    .navbar a:hover,
    .dropdown:hover .dropbtn {
      background-color: #575757;
    }

    .dropdown {
      position: relative;
      display: inline-block;
    }

    .dropdown-content {
      display: none;
      position: absolute;
      background-color: #f9f9f9;
      min-width: 180px;
      box-shadow: 0px 8px 16px rgba(0,0,0,0.2);
      z-index: 1;
    }

    .dropdown-content a {
      color: black;
      padding: 12px 16px;
      text-decoration: none;
      display: block;
      text-align: left;
    }

    .dropdown-content a:hover {
      background-color: #f1f1f1;
    }

    .dropdown:hover .dropdown-content {
      display: block;
    }

    /* Responsive */
    @media screen and (max-width: 600px) {
      .navbar {
        flex-direction: column;
        align-items: stretch;
      }
    }
  </style>
</head>
<body>

  <!-- Header / Banner -->
  <div class="header">
    Mengting Han Lab
  </div>

  <!-- Navigation Bar -->
  <div class="navbar">
    <div class="dropdown">
      <button class="dropbtn">Home</button>
      <div class="dropdown-content">
        <a href="#">Welcome</a>
        <a href="#">News</a>
      </div>
    </div>

    <div class="dropdown">
      <button class="dropbtn">Research</button>
      <div class="dropdown-content">
        <a href="#">Current Projects</a>
        <a href="#">Past Work</a>
        <a href="#">Collaborations</a>
      </div>
    </div>

    <div class="dropdown">
      <button class="dropbtn">Publications</button>
      <div class="dropdown-content">
        <a href="#">Journal Articles</a>
        <a href="#">Conference Papers</a>
        <a href="#">Posters</a>
      </div>
    </div>

    <div class="dropdown">
      <button class="dropbtn">People</button>
      <div class="dropdown-content">
        <a href="#">PI</a>
        <a href="#">Graduate Students</a>
        <a href="#">Alumni</a>
      </div>
    </div>

    <div class="dropdown">
      <button class="dropbtn">Lab Photos</button>
      <div class="dropdown-content">
        <a href="#">Events</a>
        <a href="#">Conferences</a>
        <a href="#">Outreach</a>
      </div>
    </div>

    <div class="dropdown">
      <button class="dropbtn">Contacts</button>
      <div class="dropdown-content">
        <a href="#">Email</a>
        <a href="#">Location</a>
        <a href="#">Social Media</a>
      </div>
    </div>
  </div>

</body>
</html>
