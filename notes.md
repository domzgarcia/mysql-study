<details>
 <summary>Usual action to inspect Database</summary>
 <ul>
  <li>show databases;</li> 
  <li>SELECT DATABASES();</li> 
  <li>DROP DATABASE IF EXISTS testDB;</li> 
  <li>1. CREATE DATABASE testDB;</li>
  <li>2. USE testDB;</li> 
  <li>3. SHOW TABLES;</li>
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
 <summary><b>Lesson 1: What is a Primary Key?</b></summary>
 <ul>
  <li>Uniquely identifies a row or record.</li>
  <li>Each Primary Key must be unique to the row.</li>
  <li>Must be given a value when the row is created and that value can't be NULL.</li>
  <li>The original value can't be changed.</li>
  <li>It's probably best to auto increment the value of the key.</li>
 </ul>
</details>

<details>
 <summary><b>Lesson 2: Atomic Tables & Table Templating</b></summary>
 <ul>
  <li>Every table should focus on describing just one thing.</li>
  <li>After you decide what one thing your table will describe, then decide what things you need to describe that thing.</li>
  <li>Write out all the ways to describe the thing and if any of those things requires multiple inputs, pull them out.</li>
 </ul>
</details>


<details>
 <summary>Template</summary>
 <ul>
  <li>
<pre>
Content
</pre>
  </li>
 </ul>
</details>


<details>
 <summary>Template</summary>
 <ul>
  <li>
<pre>
Content
</pre>
  </li>
 </ul>
</details>
