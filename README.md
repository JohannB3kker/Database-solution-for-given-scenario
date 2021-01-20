# Database solution for given scenario


Johann Bekker YJPCWYF29 Class 3A (ITDA310 Project submission)

For this project I had to create a database solution (Health Information System) to link a hospital, community and healthcare workers. All requirements were gathered by analysing all three given scenarios. I had to ensure that my solution supports these various scenarios (please refer to the project documentation file).  The interface application allow clinicians to enter a diagnosis, examination findings, a prescription, a treatment request and schedule a follow-up appointment. Clinicians are also able to see results of treatments.  

The project (ZIP file) contains the following:
*Documentation (Johann Bekker YJPCWYF29 ITDA310 Project documentation)
*Java database interface (ClinicianDatabaseInterface)
*Database (johannBekkerBroadReachITDA310ProjectDatabase)
*Project questions and scenario

How to run:
1. Ensure that you have the latest version of the NetBeans IDE installed.
2. Ensure that you have MySQL Workbench 8.0 CE installed.
3. Open the NetBeans IDE.
4. Open the Java database interface (ClinicianDatabaseInterface) through the NetBeans IDE.
5. Navigate to the connectToDatabase() method.
6. Find the "conn = DriverManager.getConnection(path, "root", "P@ssword1");" line.
7. Change the username and password of the server ("root" and "P@ssword1") to your
   credentials used to access your server.
8. Run the database (johannBekkerBroadReachITDA310ProjectDatabase).
9. Run the Java database interface (ClinicianDatabaseInterface).
