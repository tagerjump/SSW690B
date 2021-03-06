***SignUp:***

**Inputs:**
* Email ID
* Password
* Forget Password

**Outputs:**
* getsLoggedIn (gets sessionID if email id & password matched)

***getHomePage:***

**Inputs:**
* sessionId

**Outputs:**
* DOD HomePage
* About Us 
* Profile
* I need a Doc
* Careers
* Contact Us

***getProfile: (Patient)***

**Inputs:**
* sessionID

**Outputs:**
* patients picture
* name
* address
* city
* state
* zipcode
* country
* gender
* phone
* Past History/Record

***getProfile: (Doctor)***

**Inputs:**
* sessionID

**Outputs:**
* doctors picture
* name
* address
* city
* state
* zipcode
* country
* gender
* phone
* certificates
* licence
* degree

***getPaymentSetupDetails:***

**Inputs:**
* sessionID

**Outputs:**
* Card Number
* Expiration mm/yyyy
* Card Type
* Billing Address

***getQuestionnarie: (For Patients)***

**Inputs:**
* sessionID

**Outputs:**
* List of different types of body parts 
* List of different questions for diagnosis

***getListOfDOCTORS:***

**Input:**
* QuestionnairePageSubmit

**Outputs:**
* List of Doc Available
* List of Doc Busy
* List of Doc Offline

***getPatientsList: (For Doctors)***

**Input:**
* sessionID

**Output:**
* GetsPatientlist 
* Number of unread messages

***getChatHistory:*** 

**Inputs:**
* sessionID_patient
* sessionID_doctor

**Outputs:**
* Complete ChatDetails
* Doctor advices, details, and prescription
