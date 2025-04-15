# testphp1
<?php
// this is my frist PHP code
/* this 
is 
multi 
line 
comment */
echo "ahmed ";
print " Alamir  ";
$arr = ['ahmed','alamir','saied'];
echo "<br>";
print_r($arr);
// print in php
//$variable = "AHMED"
$arr = ['Ahmed'];
echo "<br>";
print_r($arr);
$fristName ="Ahmed"; // concatination
$lastName = "Alamir"; // Camel Cass
echo "<br>"; // new line print
echo $fristName . " " . $lastName; // concatination print
$age = "38";
echo "<br>";

echo "Age = ";
echo $age;
echo "<br>";
define("NAME","Ahmed");//constant
echo NAME;
echo "<br>";
const AGE = " 38 "; //constant
echo AGE;
echo "<br>";
echo "Back-End Developer Programming languages";
echo "<br>";
//multi concatination
$ProgrammingLanguages ="1-Python 2-PHP 3-JavaScript 4-Ruby 5-Java 6-C#";
$frameWorks = "1-Laravel 2-Django 3-Spring 4-Ruby on Rails 5-Meteor 6-Node.js";
$dataBase ="1-MongoDB 2-MySQL 3-Oracle";
$Servers ="1-Apache 2-NGINX 3-Lighttpd 4-Microsoft IIS";
echo $ProgrammingLanguages ."". $frameWorks;
echo "<br>";
echo $dataBase ."". $Servers;
echo "<br>";
$fristName = "Ahmed-";
$lastName = "Alamir ";
$universityName = " University 6 October -";
$college = " Computer science ";
echo $fristName ."". $lastName ."". $universityName ."". $college ;
echo "<br>";
/*
$Name = "Alamir"
const Age = "38";
print Age ."". $Name ; (this code dos't print)
*/
// Escape sequence print
echo 'How to become a back-end "developer" ?';
echo "<br>";
echo "Learn back-end development \"today\"";

?>
