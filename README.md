# database-final-project-solved
**TO GET THIS SOLUTION VISIT:** [Database Final Project Solved](https://www.ankitcodinghub.com/product/database-final-project-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95496&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Database Final Project Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
In this term project, you are required to do the followings:

1.Design and setup your database with the provided data.

2.Create a Java application with GUI that is capable of interacting with the database. 3.Correctly Implement the queries in SQL.

Design and Setting Up the Database

MariaDB, which is open-source variant of MySQL, is going to be used in this project. You would need to first install it on your computer.

Installation

Windows Installation package can be found here https://mariadb.org/download/. Things are pretty easy on Windows. Simply run the installation program and follow its instructions will do the job. Remember to tick the check box for “Allow remote root access” as well as taking a note of your root password and server port number. After installation, run the “Command Prompt (Mariadb)” program to access your database.

Linux You can install it via apt-get if your system does not have it already. first do sudo apt update

Then

<pre>    sudo apt install mariadb-server
</pre>
Finally

<pre>    sudo mysql_secure_installation
</pre>
You will be greeted by a few questions related to configurations of the database. First following the instruction and set a root password. Then proceed following the settings below.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Data Base: Final Project

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>New password:
Re-enter new password:
Password updated successfully! Reloading
privilege tables..
</pre>
…Success!

By default, a MariaDB installation has an anonymous user, allowing anyone to log into MariaDB without having to have a user account created for them. This is intended only for testing, and to make the installation go a bit smoother. You should remove them before moving into a production environment.

<pre>Remove anonymous users?[Y/n] Y
 ...Success!
</pre>
Normally, root should only be allowed to connect from ‘localhost’. This ensures that someone cannot guess at the root password from the network.

<pre>Disallow root login remotely?[Y/n] n
 ...skipping.
</pre>
By default, MariaDB comes with a database named ‘test’ that anyone can access. This is also intended only for testing, and should be removed before moving into a production environment.

<pre>Remove test database and access to it?[Y/n] Y
 -Dropping test database...
 ...Success!
 -Removing privileges on test database...
 ...Success!
</pre>
Reloading the privilege tables will ensure that all changes made so far will take effect immediately.

<pre>Reload privilege tables now?[Y/n] Y
 ...Success!
</pre>
<pre>Cleaning up...
</pre>
All done!If you ‘ve completed all of the above steps, your MariaDB installation should now be secure.

Thanks for using MariaDB!

After installation, run the following command to access your database.

<pre>    sudo mysql -u root -p
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Data Base: Final Project

</div>
</div>
<div class="layoutArea">
<div class="column">
MacOS MacOS is not recommended for this project. If you insist on doing it with a Mac, here a link that might be useful for you. https://mariadb.com/kb/en/installing-mariadb-on-macos-using-homebrew/

Creating and Loading data into Your Database

Designing your Database You should be design the schema of your database using ER- diagram. Primary keys, Foreign Keys and other constraints should be properly applied to tables during this phase.

Creating the Database After you log into your database server for the first time, what you need to do is creating a database. You can use the CREATE DATABASE statement to do so. After doing so, select your database with the USE statement. Now you are ready for creating actual4 tables and filling them with data in this database.

Additional Information CSV files can be loaded into the database using the LOAD DATA Statement. Be sure to add the “LOCAL” keyword otherwise there might be permission problems. See details here. https://dev.mysql.com/doc/refman/8.0/en/ load-data.html

Interface

Once your work with the database is done, you can move on to coding the Java application that deals with it. Three UI components are required, all other things are optional.

As shown in the figure right:

1.Table list area, where the user should be able to click on one of themcheck the corresponding contents in the re- sult area below.

2.input form, where the user could input SQL statement and submit it to the server to execute. Note: your input form should NOT accept “DROP” operation.

3.result area, where either error mes- sage or the results show here.

The layout of the UI is all up to you and you don’t have to make it nice looking.

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Data Base: Final Project

</div>
</div>
<div class="layoutArea">
<div class="column">
Data and Queries

In data.zip (which can be found in the “Files” section on Canvas), there are csv and txt files. The csv files are the data you need to put into your database, while the query.txt contains 20 queries you need to implement in SQL language, which I will test through your Java app.

Deliverable

What you need to turn in is a zip file, named like your_auburn_username.zip which should contain:

1.All source files for your Java app.

2.An sql.txt contains all your sql statements which solves the questions in query.txt. 3.The ER-diagram of your database.

Coding Hints Sample Code

Below is piece of sample code that I wrote to show you how you can interact with MariaDB in Java.

packagesqlSample; importjava.sql.Connection; importjava.sql.DriverManager; importjava.sql.SQLException; importjava.sql.Statement; importjava.sql.ResultSet;

publicclassexec{ publicstaticvoidmain(String[]args){

try{

</div>
</div>
<div class="layoutArea">
<div class="column">
// The newInstance() call is a work around for some

// broken Java implementations Class.forName(“com.mysql.cj.jdbc.Driver”).getDeclaredConstructor()

<pre>                                                     .newInstance();
</pre>
<pre>String dbName="Your Database Name"; String
port="Your Database Server Port"; String
pwd="Your root Password";
Connection conn=DriverManager.getConnection("jdbc:mysql://localhost:"
</pre>
+port+”/”+dbName+”?”+ “user=root&amp;password=”+pwd);

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Data Base: Final Project

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>    Statement stmt=conn.createStatement();
    ResultSet rs=stmt.executeQuery("SELECT * FROM Planets");
</pre>
while(rs.next()){ intid=rs.getInt(“ID”);

String name=rs.getString(“name”); System.out.println(id+”—“+name);

}

}catch(SQLException ex){

// handle the error

System.out.println(“SQLException: “+ex.getMessage()); System.out.println(“SQLState: “+ex.getSQLState()); System.out.println(“VendorError: “+ex.getErrorCode());

}

catch(Exception e) {

System.out.println(“Unkown Error:”+e.getMessage()); }

</div>
</div>
<div class="layoutArea">
<div class="column">
} }

Working with the JDBC driver

The following piece of code requires the help of a JDBC driver to work. It’s jar file which you can download from Canvas via the link in the project details. To run your java code with the driver, first compile your code into classes via javac, then put the driver jar into your current working folder and run:

<pre>java -cp".;mysql-connector-java-8.0.16.jar"YourPackage.YourMainClass
</pre>
Or you can add the location of the driver jar into your classpath and run your code directly.

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
