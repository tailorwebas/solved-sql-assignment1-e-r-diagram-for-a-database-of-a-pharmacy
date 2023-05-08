Download Link: https://assignmentchef.com/product/solved-sql-assignment1-e-r-diagram-for-a-database-of-a-pharmacy
<br>



<ol>

 <li>Plan an E-R Diagram for a database of a pharmacy. The requirements are given below. The diagram must include all entity sets, their attributes, and the relations sets between the entity sets.  You may add additional attributes or relationships beyond what is specified.  Do not forget to show the primary key(s) for each entity set and the cardinality of the relationships (one-to-one, one-to-many, etc.)</li>

</ol>

Patients come with a prescription from their doctor and buy the drugs from the pharmacy.  The pharmacy needs to keep track of the patients, the doctors, the drugs, and the suppliers of the drugs.

<ul>

 <li>The pharmacy database stores this information about the customers:

  <ul>

   <li>Customer ID</li>

   <li>Name (first, middle, last) o Address (street, number, city, zip code) o Phone number o Email o Date of birth o Name of insurance company.</li>

  </ul></li>

</ul>

<ul>

 <li>The pharmacy database stores this information about doctors:

  <ul>

   <li>Name (first, middle, last) o Medical license number o Specialty o Phone number(s)</li>

  </ul></li>

</ul>

<ul>

 <li>The pharmacy database stores this information about prescriptions:

  <ul>

   <li>Patient o Doctor o Drug o Dose o Date</li>

  </ul></li>

</ul>

<ul>

 <li>The pharmacy database stores this information about drug suppliers:</li>

</ul>

o Supplier ID o Supplier name o Address (street, number, city, zip code) o Phone number(s)

<ul>

 <li>The pharmacy database stores this information about drugs it sells: o Drug name o Supplier o Supplier catalog number o Amount in inventory</li>

</ul>

A doctor can prescribe one or more drugs to a patient.  A doctor writes prescriptions to many patients, and a patient can get prescriptions from more than one doctor.  A doctor can write a repeat prescription (same drug to the same patient) on different dates.  The same prescription cannot be written twice on the same day.  Each prescription specifies the amount of the drug given to the patient.

Each drug comes from exactly one supplier.  If a supplier stops working with the pharmacy, all the drugs in inventory are returned to the supplier and the supplier is deleted from the database.




<ol start="2">

 <li>Below is an ERD for a college. Transform it into tables.</li>

</ol>


