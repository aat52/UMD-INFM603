## Data Integration

In this assignment we will do some data cleaning and enhancement, create linked data, and then use that linked data to answer some SPARQL queries.  The two sources that we will use are:
* Wikidata (https://www.wikidata.org/)
* NASA Flight Controllers Table (https://www.mannedspaceops.org/ -- select Personnel from the top menu bar, and then Master Database)

You will do this in four steps:

1. Add one new column to the spreadsheet for each mission that indicates the shift number (1, 2, 3, 4) for people who served on a known shift on that mission.  You can do this in OpenRefine, Excel, python, or in any other way you want.  Later in this assignment you will use shift data for Apollo 17, so you need to do this for at least that mission.  But if you do this in an automated way (as I would encourage) then there is no reason not to do it for every mission.   
2. Clean the person names by dividing them into four parts: prefix, if any (e.g., Dr. or Lt. Col.), given names (e.g., Bruce W.), family name (McCandless), and suffix, if any (e.g., M.D. or Jr.).  You can do this with Excel, OpenRefine, python, or any other way you want.
3. Use the improved person names with OpenRefine and Knolbase to improve the reconciliation of individuals to Wikidata identifiers for as many of those people as is reasonably possible.  Don't spend too much time on details that would require learning new domain knowledge about the Mission Control Center, though.  Store the reconciliation results as an additional column, replacing the one that is there now.  When you finish this, export an .xlsx spreadsheet.
4. Use OpenRefine with RDF Transformer to generate Linked Data from your improved spreadsheet for at least Apollo 17.  Improve over what we had in class in at least two ways.  First, use an existing ontology (e.g., Wikidata) to represent the (up to) four parts of each name that you found in step 2 using linked data.  Second, represent the shift number for people who have an assigned shift.  You may make other improvements too if you wish (e.g., you could represent all the missions rather than just Apollo 17, or you could replace FOAF and VCard with Wikidata relations), but that is not required.
5. Load your linked data in Fuseki and then create a SPARQL query to find the name and work location of the Shift 1 Flight Director on Apollo 17.  Also create two other SPARQL queries that find different things in your linked data that you find interesting (for example, you might look for people who have the same last name, and thus might be related, and then check to see if they worked together in the same room).

Upload to ELMS a document (in Word, PDF, or text) with your SPARQL queries, an explanation of each query's goal, the result of each query, and Turtle linked data representations for at least 20 representative entities.  Also upload your improved Excel spreadsheet as a separate file.

- [x] Correct shift numbers in spreadsheet for at least Apollo 17.
- [x] Correct handling of prefixes, given names, family name and suffixes for more than half of the people that were not initially correct in the spreadsheet.
- [x] Correct linking to Wikidata identifiers of several names that were not previously correctly linked, as indicated by identifier values in the added spreadsheet column.
- [x] Correct generation of linked data triples in Turtle format for at least 20 representative individuals that match the content of the updated spreadsheet.
- [x] At least three SPARQL queries, including one that meets the specific requirements of the assignment (including the correct birthday).


### Score: 5/5
| Criteria | Comments | Points |
| ----------- | ----------- |  ----------- |
| Shift Numbers | Great job and organization! | 1/1 |
| Name Cleanup | Nice! Even if it did pick up some nicknames/preferred names as suffix, that is ok | 1/1 |
| Name Resolution | Nice job! | 1/1 |
| Linked Data Triples| Great job! | 1/1 |
| SPARQL Queries | Great queries. | 1/1 |

