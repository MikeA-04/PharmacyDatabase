# (CS480) Pharmacy Database Project
This application allows a user to easily interact with our pharmacy database by allowing it to only insert, delete, update, search, and list data.\
The entity-relationship diagram for the pharmacy database is as seen below or in 'ProjectPart1.pdf', which also contains the database decription and schema:\
<img src="https://user-images.githubusercontent.com/69696262/184795605-19356d00-16eb-4274-820e-dde10f64aeb6.png" width=60% height=60%> <br><br>
The image below is a screenshot of what the user sees upon running the program, which allows the user to enter data into the 'patient' table.\
All the fields must be filled in and correctly formatted, or else the tuple will be rejected.\
<img src="https://user-images.githubusercontent.com/69696262/184795983-b1a55759-07ba-4704-8de1-0cb0a2d1e31d.png" width=60% height=60%> <br><br>
The following images show the delete, update, search, and list screens for the 'patient' table:
<img src="https://user-images.githubusercontent.com/69696262/184796298-99823b18-36ff-42dc-9a21-b00ed1208895.png" width=60% height=60%> <br><br>
<img src="https://user-images.githubusercontent.com/69696262/184796357-a57d981a-2142-4cfb-a09f-fac788e3aa7d.png" width=60% height=60%> <br><br>
<img src="https://user-images.githubusercontent.com/69696262/184796441-237ba842-8360-493c-9fa7-3b39e4151f72.png" width=60% height=60%> <br><br>
<img src="https://user-images.githubusercontent.com/69696262/184796523-c625cf71-42e8-4beb-8a8a-a6cfe1150c52.png" width=60% height=60%> <br><br>
Here is a screenshot that lists all the data from the 'patient' table, which can be triggered by clicking the "List" button:
<img src="https://user-images.githubusercontent.com/69696262/184796724-0bd54ceb-01ea-493f-a296-c15c629160d9.png" width=60% height=60%> <br><br>
There are six more menu items that allow the user to see data that must be calculated or imported from various tables. They are as labeled below, which is followed by a description:\
**"Cheapest Medication Forms"** - lists all the medication names with their cheapest form and price.\
**"Non-Adult Patients"** - lists the patients' name, birth date, prescription number, refills left, quantity, and doctor for all the prescriptions that correspond to patients under 18 years old.\
**"Hormonal Agents"** - lists all the medication's name, form, price, stock status, and drug class where the drug class is any kind of hormonal agent.\
**"Prescription Meds by Doctor"** - lists all the doctors who have prescribed medications grouped by drug class and their count (i.e., "Sam Smith, MD" has prescribed medications in the "blood product" class "3" times).\
**"Average Medication Price"** - lists all the medications and their average prices, which takes into account all their forms available in the database.\
**"Doctors to Call for RX"** - lists all the patients' names, birth dates, prescription numbers, and doctor's information where the medication is tied to an "OUT_OF_STOCK" form.
