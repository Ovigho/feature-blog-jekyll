The if, elseif ...else and switch statements are used to take decision based on the different
condition.
You can use conditional statements in your code to make your decisions. PHP supports the
following three decision making statements:
 if...else statement - use this statement if you want to execute a set of code when
a condition is true and another if the condition is not true
 elseif statement - is used with the if...else statement to execute a set of code if
one of several condition are true
 switch statement - is used if you want to select one of many blocks of code to be
executed, use the Switch statement. The switch statement is used to avoid long
blocks of if..elseif..else code.
The If...Else Statement
If you want to execute some code if a condition is true and another code if a condition is
false, use the if....else statement.
Syntax
if (condition)
code to be executed if condition is true;
else
code to be executed if condition is false;
Example
The following example will output "Have a nice weekend!" if the current day is Friday,
otherwise it will output "Have a nice day!":
<html>
<body>
<?php
$d=date("D");
if ($d=="Fri")
echo "Have a nice weekend!";
else
echo "Have a nice day!";
?>
