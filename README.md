# online-voting-system
(4-2018)
Online Voting System Basic Interface and working project [ HOSTED]

(Report me if Website sleeping)

Distributed Online Voting system ( HTTP )
Includes PHP files, html, css


Vote via Web Interface

SQL includes database polling_system consisting of tables:
1. registered : (
  `Name` varchar(100) NOT NULL,
  `Email` varchar(100) NOT NULL,
  `Password` varchar(100) NOT NULL
)
2. poll_done : (
  `email` varchar(100) NOT NULL
)
3. choice  : Include all columns of candidate lists based on "value" of radio buttons in tp.php file


<h3>Overview</h3>
Registration / Login system

Redirects to Sucess page once voted sucessfully
Registers vote in Database and registers entry in poll_done
User once voted will be logged out automatically and wont be able to login again.
