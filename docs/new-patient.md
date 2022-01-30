## New Patient Registration and Management 
CDMS follows the <b>PHN (Personal Health Number)</b> concept introduced by the Ministry of Health. <i><u>A PHN is unique to a given patient</i></u> and is created wherever the patient visits first. Like landline telephone numbers, PHNs have a unique first few digits which tell where the PHN was first created. For Anuradhapura teaching hospital, it is 0591xxxxxx – xxxx being the individual patient number. Wherever a patient visits (e.g., NHSL Colombo) – this PHN will be the same and will not change. 

The goal of a PHN is to maintain a continuous medical record wherever a patient visits in the country. 
The current health ministry software which generates the PHN number is having technical issues with CDMS  - and only in TH Anuradhapura, the two systems talk to each other to get PHN information. 
In all other hospitals, you need to manually register the PHN in CDMS. In most hospitals where a PHN is issued it is printed on the admission sheet using a barcode.
Examples of where you can find a patient’s PHN : 

<img src="/img/phn-patient-card.png" alt="PHN Card example" width="300px" >

<b>Note : although when printed the PHN is printed with XXXX-XXXXXX-X format, the actual PHN has no dashes. <u> So, if entering the PHN don’t use dashes.</u> </b>

The use of BHT number as a patient identifier should be stopped as BHT numbers are admission specific – and they don’t cater to clinic visits. 
If your PC is equipped with a barcode scanner, use the scanner to scan the PHN wherever you are required to enter the PHN. This avoids errors in typing the PHN

<b>DO NOT USE BHT NUMBERS TO IDENTIFY PATIENTS! </b>

### Manually Register PHN

Once you know the PHN (e.g from clinic note, admission note etc..), you need to register the patient on CDMS using that PHN as follows. Note : For Anurdhapura users, this step is not necessary. They can automatically “pull” in a patient to CDMS (Read section on getting patients from HHIMS). 

Click Add New Patient <img src="/img/nav-add-patient.jpg" alt="Nav Bar Add Patient" width="40px" > on the navigation bar 

You will be presented with this warning. Its basically to remind you that you should use the PHN to register the patient on CDMS. Click OK to proceed

<img src="/img/add-patient-warning.png" alt="Add patient warning." width="500px" >

Most fields are self-explanatory. 

<img src="/img/addpatient.png" alt="Add patient details." width="800px" >


For age - if you do know the exact birth date – enter it as given. If only age is known, just enter the age. The system will create the date as for June 1st of the birth year corresponding to the patient’s age.<b> Note – for children, birth date is mandatory </b>

If the PHN already exists, it will give a warning. If you want to EDIT that PHN, you can do by click “click here to edit” 

Once you have entered details, press Save and there will be a confirmation box like this stating that the PHN was successfully created. If there were errors, they will be displayed. If you want to enter another patient can click Add another. If you want to use this patient immediately, press Load this Patient to Dashboard 

<img src="/img/newphncreated.png" alt="New PHN created notice." width="400px" >

### HHIMS Integration


For users with HHIMS, you can pull the patient from HHIMs. Click the magnifying icon (search icon) and the From HHIMS tab: 

<img src="/img/hhimspull.png" alt="HHIMS Pull." width="800px" >

If the PHN is not in CDMS, you will be prompted to load it. If it is already present, then you have to option of reloading it from HHIMS (This is useful when demographic details have been changed in HHIMS  to update CDMS.

