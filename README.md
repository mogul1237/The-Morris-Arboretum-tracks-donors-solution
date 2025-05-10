# The-Morris-Arboretum-tracks-donors-solution

Download Here: [The Morris Arboretum tracks donors solution](https://jarviscodinghub.com/assignment/the-morris-arboretum-tracks-donors-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

The Morris Arboretum tracks donors to their organization in Microsoft Excel. The Arboretum also uses Excel to store a list of plants in stock. As donors contribute funds to the Arboretum, they could elect to receive a plant ‘gift’ of appreciation from the Arboretum. You plan to continue gifting plants to donors as part of the Arboretum’s membership drive. The organization has grown and the files are too inefficient to handle in Excel, however, so you decide to use Microsoft Access for future Arboretum records. In the following project, you convert Excel files into an Access database for Morris Arboretum.

Instructions:

For the purpose of grading the project you are required to perform the following tasks:

Step
Instructions
Points Possible
1
Start Access. Open the downloaded Access file named exploring_a02_grader_h1.
0
2
Create a new table in Datasheet view using the name Donations. Switch to Design View and change ID to DonationID. Add the following field names to the table: DonorID, PlantID, DonationDate, and DonationAmount (in that order).
8
3
Change the Data Type for the DonorID and PlantID fields to Number. Change the Data Type for the DonationDate field to Date/Time, and then change the Data Type for the DonationAmount field to Currency.
6
4
View the table in Datasheet view and then add the following records to the Donations table letting Access assign the DonationID:
DonorID PlantID DonationDate DonationAmount

24 15 7/17/2014 1200

9 11 8/1/2014 1500

14 9 8/15/2014 150

3 4 9/1/2014 1250

18 7 9/2/2014 4600

14 11 9/9/2014 450
6
5
Sort the records in the Donations table by the DonationAmount field in descending order. Save and close the table.
4
6
Import the downloaded a02_grader_h1Plants.xlsx workbook as a new table in the current database. Using the wizard, specify that the first row contains column headings, set the PlantID field to be indexed with no duplicates, and set the PlantID field as the primary key. Import the table with the name Plants and do not save the import steps.
10
7
View the Plants table in Design view and change the field size for the PlantID field to Long Integer. Save the table and the changes to the design of the table. Click Yes in the dialog box indicating that some data may be lost. Close the table.
4
8
Begin establishing relationships in the database by adding the Donations, Donors, and Plants tables to the Relationships window. Close the Show Table dialog box. Create a one-to-many relationship between the DonorID field in the Donors table and the DonorID field in the Donations table, enforcing Referential Integrity. Select the option to cascade update the related fields.
10
9
Create a one-to-many relationship between the PlantID field in the Plants table and the PlantID field in the Donations table. Enforce Referential Integrity. Select the option to cascade update the related fields. Save and close the Relationships window.
6
10
Create a query using the Simple Query Wizard. From the Donations table, add the DonorID and DonationAmount fields (in that order). Ensure the query is a Detail query. Name the query Donations over 500 and finish the wizard.
10
11
View the query in Design view, and then set the criteria for the DonationAmount field so that only donations greater than 500 are displayed.
6
12
Sort the query in descending order by the DonationAmount field. Save the query. Run the query and then close the query.
4
13
Create a new query in Design view. Add the Donations, Donors, and Plants tables to the query design window. Close the Show Table dialog box. Add the DonationDate field from the Donations table, the donor’s Lastname, Firstname, and Phone fields from the Donors table (in that order).
8
14
Add the DonationAmount field from the Donations table after the Phone field, and then add the PlantName field from the Plants table.
6
15
Sort the query in ascending order by the date of the donation and then by the last name of the donor in ascending order. Save the query with the name Plant Pickup List, and then run the query. Close the query.
12
16
Close all database objects. Close the database and then exit Access. Submit the database as directed.
0

Total Points
100


