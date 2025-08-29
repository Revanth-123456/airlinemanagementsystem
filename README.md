# Step 1: Download & Extract

Download the Airline Management System zip file.

Extract the contents to a folder on your computer.

Open NetBeans IDE.

Go to File → Open Project and select the extracted project folder.

# Step 2: Download Required Libraries

You need the following .jar files:

mysql-connector-java-8.0.28.jar (for database connection)

jcalendar-tz-1.3.3.4.jar (for calendar/date picker)

rs2xml.jar (for converting ResultSet to TableModel)

Make sure all three are downloaded and stored in a safe folder (example: C:\Libraries).

# Step 3: Add JAR Files to NetBeans Project

In NetBeans, right-click on your project in the Projects window.

Select Properties.

In the Project Properties window, click Libraries (left panel).

Choose the Compile tab.

Click Add JAR/Folder.

Browse to the folder where you saved the .jar files.

Select all the required JARs (mysql-connector, jcalendar, rs2xml) and click Open.

Click OK to close the Properties window.

👉 Now your project knows where the libraries are.

# Step 4: Set Main Class

In the Projects window, expand your project.

Locate login.java.

Right-click → Select Run File (to test run).

OR -

If needed, go to Project Properties → Run.

Set Main Class to login.

# Step 5: Run the Project

Click the Run Project button (green ▶ icon) in the toolbar, or press F6.

The project should start with the Login screen.
