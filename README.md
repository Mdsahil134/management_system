<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Dashboard</title>
    <link rel="shortcut icon" href="./images/download.jpg">
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons+Sharp" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header>
        <div class="logo" title="University Management System">
            <img src="./images/download.jpg" alt="University Management System Logo">
            <h2>U<span class="danger">M</span>S</h2>
        </div>
        <div class="navbar">
            <a href="index.html" class="active">
                <span class="material-icons-sharp">home</span>
                <h3>Home</h3>
            </a>
            <a href="timetable.html" onclick="timeTableAll()">
                <span class="material-icons-sharp">today</span>
                <h3>Time Table</h3>
            </a>
            <a href="exam.html">
                <span class="material-icons-sharp">grid_view</span>
                <h3>Examination</h3>
            </a>
            <a href="password.html">
                <span class="material-icons-sharp">password</span>
                <h3>Change Password</h3>
            </a>
            <a href="#" onclick="logoutFunction()">
                <span class="material-icons-sharp">logout</span>
                <h3>Logout</h3>
            </a>
        </div>
        <div id="profile-btn">
            <span class="material-icons-sharp">person</span>
        </div>
        <div class="theme-toggler">
            <span class="material-icons-sharp active">light_mode</span>
            <span class="material-icons-sharp">dark_mode</span>
        </div>

    </header>
    <div class="container">
        <aside>
            <div class="profile">
                <div class="top">
                    <div class="profile-photo">
                        <img src="./images/profile-1.jpg" alt="">
                    </div>
                    <div class="info">
                        <p>Hey, <b>Alex</b> </p>
                        <small class="text-muted">12316787</small>
                    </div>
                </div>
                <div class="about">
                    <h5>Course</h5>
                    <p>BTech. Computer Science & Engineering</p>
                    <h5>DOB</h5>
                    <p>01-Jan-2004</p>
                    <h5>Contact</h5>
                    <p>9876543210</p>
                    <h5>Email</h5>
                    <p>unknown@gmail.com</p>
                    <h5>Address</h5>
                    <p> Near GT Road , Lovely Professional University , Phagwara , Punjab , 144411 </p>
                </div>
            </div>
        </aside>

        <main>
            <h1>Attendance</h1>
            <div class="subjects">
                <div class="eg">
                    <span class="material-icons-sharp">architecture</span>
                    <h3>CHE110: ENVIRONMENTAL STUDIES</h3>
                    <h2>24/26</h2>
                    <div class="progress">
                        <svg><circle cx="38" cy="38" r="36"></circle></svg>
                        <div class="number">
                            <p>92%</p>
                        </div>
                    </div>
                    <small class="text-muted">Last 24 Hours</small>
                </div>
                <div class="eg">
                    <span class="material-icons-sharp">functions</span>
                    <h3>MTH174: ENGINEERING MATHEMATICS</h3>
                    <h2>27/29</h2>
                    <div class="progress">
                        <svg><circle cx="38" cy="38" r="36"></circle></svg>
                        <div class="number">
                            <p>93%</p>
                        </div>
                    </div>
                    <small class="text-muted">Last 24 Hours</small>
                </div>
                <div class="cs">
                    <span class="material-icons-sharp">computer</span>
                    <h3>INT108: PYTHON PROGRAMMING</h3>
                    <h2>27/30</h2>
                    <div class="progress">
                        <svg><circle cx="38" cy="38" r="36"></circle></svg>
                        <div class="number">
                            <p>90%</p>
                        </div>
                    </div>
                    <small class="text-muted">Last 24 Hours</small>
                </div>
                <div class="eg">
                    <span class="material-icons-sharp">dns</span>
                    <h3>ECE249: BASIC ELECTRICAL AND ELECTRONICS ENGINEERING</h3>
                    <h2>27/29</h2>
                    <div class="progress">
                        <svg><circle cx="38" cy="38" r="36"></circle></svg>
                        <div class="number">
                            <p>93%</p>
                        </div>
                    </div>
                    <small class="text-muted">Last 24 Hours</small>
                </div>
                <div class="eg">
                    <span class="material-icons-sharp">router</span>
                    <h3>CSE326: INTERNET PROGRAMMING LABORATORY</h3>
                    <h2>25/27</h2>
                    <div class="progress">
                        <svg><circle cx="38" cy="38" r="36"></circle></svg>
                        <div class="number">
                            <p>92%</p>
                        </div>
                    </div>
                    <small class="text-muted">Last 24 Hours</small>
                </div>
                <div class="eg">
                    <span class="material-icons-sharp">architecture</span>
                    <h3>PES318: SOFT SKILLS</h3>
                    <h2>27/30</h2>
                    <div class="progress">
                        <svg><circle cx="38" cy="38" r="36"></circle></svg>
                        <div class="number">
                            <p>90%</p>
                        </div>
                    </div>
                    <small class="text-muted">Last 24 Hours</small>
                </div>
                <div class="eg">
                    <span class="material-icons-sharp">computer</span>
                    <h3>CSE11: ORIENTATION TO COMPUTING-I</h3>
                    <h2>23/25</h2>
                    <div class="progress">
                        <svg><circle cx="38" cy="38" r="36"></circle></svg>
                        <div class="number">
                            <p>92%</p>
                        </div>
                    </div>
                    <small class="text-muted">Last 24 Hours</small>
                </div>
                <div class="cs">
                    <span class="material-icons-sharp">dns</span>
                    <h3>ECE279: BASIC ELECTRICAL AND ELECTRONICS ENGINEERING LABORATORY</h3>
                    <h2>27/30</h2>
                    <div class="progress">
                        <svg><circle cx="38" cy="38" r="36"></circle></svg>
                        <div class="number">
                            <p>90%</p>
                        </div>
                    </div>
                    <small class="text-muted">Last 24 Hours</small>
                </div>
            </div>

            <div class="timetable" id="timetable">
                <div>
                    <span id="prevDay">&lt;</span>
                    <h2>Today's Timetable</h2>
                    <span id="nextDay">&gt;</span>
                </div>
                <span class="closeBtn" onclick="timeTableAll()">X</span>
                <table>
                    <thead>
                        <tr>
                            <th>Time</th>
                            <th>Room No.</th>
                            <th>Subject</th>
                            <th></th>
                        </tr>
                    </thead>
                    <tbody></tbody>
                </table>
            </div>
        </main>

        <div class="right">
            <div class="announcements">
                <h2>Announcements</h2>
                <div class="updates">
                    <div class="message">
                        <p> <b>Academic</b> Summer training internship with Live Projects.</p>
                        <small class="text-muted">2 Minutes Ago</small>
                    </div>
                    <div class="message">
                        <p> <b>Co-curricular</b> Global internship oportunity by Student organization.</p>
                        <small class="text-muted">10 Minutes Ago</small>
                    </div>
                    <div class="message">
                        <p> <b>Examination</b> Instructions for End Term Examination.</p>
                        <small class="text-muted">Yesterday</small>
                    </div>
                </div>
            </div>

            <div class="leaves">
                <h2>Teachers on leave</h2>
                <div class="teacher">
                    <div class="profile-photo"><img src="./images/profile-2.jpeg" alt=""></div>
                    <div class="info">
                        <h3> Dr. Gopal Ghosh</h3>
                        <small class="text-muted">Half Day</small>
                    </div>
                </div>
                <div class="teacher">
                    <div class="profile-photo"><img src="./images/profile-3.jpg" alt=""></div>
                    <div class="info">
                        <h3>Shivani Sharma</h3>
                        <small class="text-muted">Full Day</small>
                    </div>
                </div>
                <div class="teacher">
                    <div class="profile-photo"><img src="./images/profile-4.jpg" alt=""></div>
                    <div class="info">
                        <h3>Dr. Rahul Kumar</h3>
                        <small class="text-muted">Full Day</small>
                    </div>
                </div>
            </div>

        </div>
    </div>

    <script src="timeTable.js"></script>
    <script src="app.js"></script>
</body>

</html>
