# Colab Notebook

Our goal in this assignment is simply to get  to know the Colab Notebook environment that we'll be using for all of the homework assignments in this course.  Start by making a copy of the Colab notebook that we used in class.  Then modify your copy of the notebook to build a travel record for Secretary of State Henry Kissinger for the messages in at least 20 of the files (each of which contains the messages for a month).  To do this, first find the messages sent by Kissinger. For each such message, print the date and the address of the sending organization to a file named Kissinger_Travel.txt, in increasing date order (i.e., oldest messages first).  Examining this file, you should be able to see where Kissinger as visiting each time he sent a message (although the abbreviations used in the sender's addresses might be a bit cryptic).  Make your colab notebook readable (but not writeable!) by anyone with the URL, and then submit your URL.  Don't change that Colab notebook after the submission deadline.

For your convenience, here is the additional information for this assignment that was posted to announcements:

-----

Kamran asked a good question about how to identify the sending location for a message in a state department cable.  Contrary to my expectations, this information was not specified by the National Archives in a metadata field, but it is n the message itself.  For example, in the message shown in the assignment (6725 Subject: POST- APOLLO: SPACELAB GOVERNMENT AGREEMENT), the from address is in this line of the message:

FM AMEMBASSY PARIS

So a useful heuristic would be that the first line that starts with "FM " is the from address.  Note, however, that there may sometimes be errors in the message format (for example, I suppose there might be a space before FM in some cases).  Anyhow, it should be easy to check to see if every message has exactly one line that starts with "FM " and if so that's very likely the from address and if not then inspecting the message will likely indicate what went wrong in that case.

I had also mentioned in class that although the colab notebook only processes five files, it would be good to do this for 20 files (which is 20 months), but that had not been in the assignment.  So I have added that to the assignment now.  

-----

1) The messages in the CFPF.PU files are (intentionally) missing the msgtext field, but the messages in the CFPF.TEL files do have that field.  So I suggest focusing on the files that start with CFPF.TEL.

2) I misspelled Kissinger.  Strangely enough, several people writing messages in the collection also misspelled Kissinger, so it did find some things.  But it works much better is you spell Kissinger correctly!

------

A few people have asked (directly or indirectly) how to "find the messages sent by Kissinger".  There are two ways people have tried:

When the message was sent on Kissinger's behalf (Kissinger didn't actually type these -- someone else did) then the message (in the msgtext field) will say, near the end "Kissinger".  In my own code I just looked for any message that had Kissinger in the last 10 tokens, and that seemed to work fine (I printed out many such cases, and they all looked like Kissinger used as a signature, not as someone mentioned in the message).

In the PU files there is a <from> tag that sometimes indicates that Kissinger was the author of the message, but in the TEL files that trick does not seem to work (because the <from> tag always seems to indicate the sending organization in the TEL files).  If you do want to use the metadata rather than the text of the messages, just be sure you look at enough examples to understand how those metadata fields were populated.

------

1) According to Wikipedia, Kissinger became secretary of state on September 22, 1973.  You might expect to find few (or perhaps even no) messages signed by him from before that date (he was previously the National Security Advisor, so he may have sent some messages before that date).  This should not be an issue for automatic processing, but it may be something you will want to know if you are choosing which messages to examine.

2) Yesterday (Saturday) I made a few improvements to the Session 2 Colab Notebook -- one to fix an error (it was reading the same file repeatedly; now it iterates through the files correctly) and one to focus on the .TEL files (just to save you the trouble of making that change).  As an aside, there are only 24 .TEL files, so you could process them all if you want to (although the assignment only requires processing 20 of them).

-----

### Submission: https://colab.research.google.com/drive/1WtbnDnG8Z5rfVvi3uAgueeA_1dX6-EB7?usp=sharing

### Score: 5/5
