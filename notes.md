<details>
 <summary>Usual action to inspect Database</summary>
 <ul>
  <li>show databases;</li> 
  <li>USE testDB;</li> 
  <li>SELECT DATABASES();</li> 
  <li>DROP DATABASE IF EXISTS testDB;</li> 
 </ul>
</details>

<details>
 <summary>Sample code: Create Student Table</summary>
 <ul>
  <li>
<pre>
CREATE TABLE student(
first_name VARCHAR(30) NOT NULL,
last_name VARCHAR(30) NOT NULL,
email VARCHAR(60) NULL,
street VARCHAR(50) NOT NULL,
city VARCHAR(40) NOT NULL,
state CHAR(2) NOT NULL DEFAULT "PA",
zip MEDIUMINT UNSIGNED NOT NULL,
phone VARCHAR(20) NOT NULL,
birth_date DATE NOT NULL,
sex ENUM('M','F') NOT NULL,
date_entered TIMESTAMP,
lunch_cost FLOAT NULL,
student_id INT UNSIGNED NOT NULL AUTO_INCREMENT PRIMARY KEY);
</pre>
  </li> 
 </ul>
 </summary>
</details>


<details>
 <summary>Sample code: Create Student Table</summary>
 <ul>
  <li>
<pre>
Test
</pre>
  </li>
 </ul>
</details>
