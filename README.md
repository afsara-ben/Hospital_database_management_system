# Hospital_database_management_system

> Context

This was created to computerize the events of a small clinic or part of a hospital, keeping in mind that a complete database of the whole hospital would be much more complex. There will be two modules.
The hospital has employees of different types such as, doctor, nurses, accountant, receptionist and pathologist. The receptionist controls the admission and appointment process. Doctors have a separate roaster according to which they visit their patient. Doctors and nurses work under a variety of departments. All patients must have access to every doctor’s basic information, like designation, years of experience, field of expertise etc. along with name and contact info. The doctor can view a patient’s entire history
Things like previous diagnosis and consultation, date of admission etc can be viewed by the doctor. Apart from this, the attributes of every table which are name, gender, distinct id, age, residence, blood group etc will be unique to all doctors and patients alike.
The patient can either take an appointment of a particular doctor or visit him or she can take admission in the hospital. In the case that someone takes an admission, she is assigned a seat within a room. A room can have a number of seats and the cost is calculated depending on how many seats a patient has availed. (As extra seat might be taken for the attendee of the patient). 

> Additional details:

A doctor can prescribe drugs and investigation in the prescription. The investigations are done by the pathologist and the drugs are supplied by the pharma_company. The prescription receipt shall have the name (both generic and local), registration no. of mentioned drug, drug dosage, methods of intake, time of intake, price, name of manufacturing company etc. printed on it. The doctor will issue this prescription to a particular patient and the patient can get the drug either from the hospital pharmacy or from outside. The condition is checked in the relation between them.
The accountant prepares the payments for the patient and the patient pays the bill. The bill contains the total cost a patient has to bear and has a PK, bill_ID and FK p_ID. 


![alt text](<path_relative_to_current_github_location/image.jpg>)
