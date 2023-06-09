# Access or Base Database
Design a four-table relational database for a bicycle rental service with tables for data about customers, bicycles, rental locations, and rentals.  Then implement your database in Microsoft Access or in Open Office Base, populate it with some sample customer, bicycle, rental location, and bicycle rental data and formulate a query to print the customer name, rental date, origin rental location, destination rental location, rental time, and cost.  You should design your query and sample content so that at least five rentals are displayed when your query is run.  Save your database as an Access .accdb or Base .odb file and submit it using ELMS.

Update at 10:45 PM on Wednesday September 21:

There have been two questions.  First, students who have Windows have asked how to get Access.  The answer is to go to terpconnect.umd.edu, select Office 365 for Students, and download it.  Office 365 also offers a cloud-hosted service, but the cloud-hosted service does not seem to have Access.  But if you select download, Access is one of the systems you can get.  Let me know if you have problems with this, but this should work.

The other question is what people who use Macs should do.  Here there are three answers.  First, you could gain access to a windows machine (e.g., by working with a classmate that has a windows machine).  That's certainly not required, but if it were easy it might be the easiest solution so I mention it first.  Second, you could use Open Office, which includes a relational database system called Base that is patterned on Access (but, of course.  The bug with this approach is that I didn't demonstrate Base in class, so the learning curve might be higher.  I plan to install Open Office tomorrow and if it works well for me I will record a video walking you through the same example that I used in class, but in Base rather than access.  So if you choose this option, you might want to wait a day before starting.  If you choose this option, we will gladly accept a Base database rather than an Access database.  Third, you could install a Windows emulator on your PC.  I suggest this only if you want a windows emulator for some other reason -- if so, this might be the time to install one.  But if you don't particularly want one, then this might not be a good option for you (just because you need to work through the details of the emulator installation.

Update at 9:00 PM in Thursday September 22:

I have tested Base in the Open Office package and it works fine (note: I tested the Windows version!), so if you have a Mac is should work for you there as well.  I recommend using Access if you have a PC with Windows, though, since Access is a commercial product and its user interface is a bit better designed.  To download open office, go to https://www.openoffice.org/download/index.html. -- then download and run the installation package.  As promised, I have also made a video in which I first examine an existing Base database (the Base equivalent of the Access database I demo'd in class) and then I create a new Base database from scratch.  As you will see, the process is very similar to Access, with the differences being in some of the user interface details.  I have also added a link to the demo projects.odb Download projects.odb file on the Session 4 ELMS page.  I have updated the assignment to indicate that we will accept either an .accdb or an .odb file.   Let me know if you have any questions.

Update at 4:30 PM on September 27:

A student has pointed out that if the cost depends on the number of hours that a bike was rented for (as it probably should ...) then storing the hours and the cost in the same table would violate 3NF.  That's true, and I have changed the rubric to indicate that we will accept 2NF (since we don't want to require what you would do in practice, which is to make the cost a computed value -- having the cost as a strored value is fine for this assignment, even though it violated 3NF).

| Criteria | Comments | Points |
| ----------- | ----------- |  ----------- |
| Working Access database | Nice database | 2/2 |
| Four required tables | Nice tables! | 1/1 |
| Normalization and keys | good job | 1/1 |
| Query | nice | 1/1 |
