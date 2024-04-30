# Requirements Template 


### ID: UFR-1
 
### Type/Category: -- Type and Sub-type

### Version: -- v0.1
 
### Title: User registratio 
  
### Description: -- Full description

The user access to a registration page and enters their personal information and contact details such as:
* Name
* e-mail
* Phone number
* Address
* Gender
* Age
Once the user has to select their role: Beginner, Intermediate and chef.   Depending on the selected role the user will have to give the given Role-Specific Information.
The user will have to create and confirm their password to complete the registration.
After the registration they have to do an account verification by login for the first time to validate the information. If everything is valid and correct the account will be created.


### Relations: -- List of related Requirements

### Comments: -- Additional information
If the person selects the role wrongly they can go back to select a different role.
The password should follow the following requirements:
* 8 to 10 characters 
* A combination of uppercase letters, lowercase letters, numbers, and symbols.
If the information is invalid the user will return to the registration page where they have to enter their personal information to correct any errors.
Some Role-Specific information are:

* Beginner: The user provides additional details about their current objective and dietary restrictions if any 

* Intermediate: The user should provide the difficulty they can work with and the dietary restrictions as well as the skills they want to work on.

* Chef: The user provides details about their experience, qualifications, and availability. 

 --- 

### ID: UFR-2
 
### Type/Category: -- Type and Sub-type

### Version: -- v0.1
 
### Title: User Login/Authentication Version
  
### Description: 
The user should be able to log in to the system using their credentials to get access to their account 

Input:
* Username or Email 
* Password
  
### Relations: -- List of related Requirements

### Comments: 
If user fails to login after multiple attempts there could be two-factor authentication
There could be a security measure so as to prevent hacks by blocking accounts after multiple failed login attempts.

 --- 

### ID: UFR-3
 
### Type/Category: -- Type and Sub-type

### Version: -- v0.1
 
### Title: Delete Profile
  
### Description: 
Allow users to delete their profile and all the data associated with it from the system.

How-to:
* Go into the settings 
* Select delete profile 
* Confirm decision twice to avoid mistakes 
* System will delete it all after confirmation and all data will be removed 


### Relations: -- List of related Requirements

### Comments: 
To avoid permanently deleting all the information and progress of a user in the app by accident, we would add a warning as well as remind the user of the consequences of deleting the app according. 


 --- 
