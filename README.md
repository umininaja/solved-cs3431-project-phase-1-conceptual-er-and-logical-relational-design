Download Link: https://assignmentchef.com/product/solved-cs3431-project-phase-1-conceptual-er-and-logical-relational-design
<br>
<span class="kksr-muted">Rate this product</span>




Note: Phases 2 and 3 of actually building and querying the DB will depend on this phase. Therefore, give it a careful thinking and design.

Description:

In this phase you are required to build a database for a Hospital System. You will provide the Entity Relationship Diagram (ERD), and the relational model that captures the following requirements:

<ul>

 <li>●  The hospital has many employees, for each employee we keep the ID (unique), first, and last names, job title, salary, address (street, town, zip), and their office number.</li>

 <li>●  Employees have three categories: regular employees, division managers where each one manages several regular employees, and general managers where each one manages several division managers. The three categories of employees share the same attributes mentioned above.</li>

 <li>●  There are two categories of regular employees: doctors and equipment technicians.</li>

</ul>

o The hospital has many doctors. For each doctor, in addition to the employee

attributes, we keep their specialty, medical school attended, and gender.o Equipment technicians can repair certain types of equipment. The diagram

needs to capture which types of equipment each technician can work on.● The hospital has many different types of equipment. For each type, we have the type ID (unique), model, description, operational instructions, and the number of units (actual equipment) of that type. Then, each unit (equipment) has its own serial number

(unique), the year of purchase, and the last inspection time.o Think of the types as “MRI”, “Ultrasound”, “CT Scanner”, …You can treat

these names as the Type IDo Then under, for example, “MRI”, the hospital may have many actual units…

<ul>

 <li>●  The hospital has several rooms; each room contains several equipment units. For each room we need to keep the room number (unique), currently occupied or not (flag), and the equipment units in this room.</li>

 <li>●  Each room can be used to provide multiple services or operations. Examples of these services are: Intensive care unit (ICU), Consulting room, Ward room, Emergency room, Operating room, etc. For each room, we need the model to capture the services it may provide.</li>

 <li>●  Patients are admitted into the hospital. For each patient, we keep track of their SSN (unique), first and last names, address, and Tel. number. Patients can be admitted</li>

</ul>

1

several times to the hospital, and the model should capture for each admission the

admission time (date/time of admission) and the leave time (date/time of exit).

<ul>

 <li>●  For each patient admission (visit), we need to keep track of which room(s) the patient stayed in, and the staying period for each room (start date and end date). We also need to keep track of total payment for this visit, and how much of this payment willbe covered by insurance (e.g., the percentage that the insurance will cover).</li>

 <li>●  For each patient visit, we need to keep track of which doctor(s) have examined thepatient, and the result of this examination (the doctor’s comments).</li>

 <li>●  At the end of a patient’s visit, the patient may schedule a future visit. We want themodel to capture these scheduled visits (capture the dates of these future visits).</li>

 <li>●  Employees have access to specific rooms, and we want our model to capture that.That is, capture which room(s) each employee has access to.Requirements:

  <ol>

   <li>Design an ERD that captures the above requirements. Follow the notations given in the course slides, and also follow the given guidelines for Good Design.</li>

   <li>State any assumptions that you make in addition to the above requirements.</li>

   <li>Create a relational model for the above application. You need to follow the rules that convert the ERD to relational model. The only requirement in this phase is to define the relations (tables) and their primary keys. No other constraints are required in this phase. The desired format of the relational model that you should deliver is as follows:a. If you have a relation named R with columns A1, A2, ..An and the primary key is A1, then your relational model should have:“R(A1, A2,…, An)”b. So, no Create Table statements are required in this phase.</li>

  </ol></li>