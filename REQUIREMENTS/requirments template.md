# Requirements Template 


### ID: UFR-1
 
### Type/Category: -- Type and Sub-type

### Version: v0.1
 
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

### Version: v0.1
 
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

### Version: v0.1
 
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

### ID: CFR-1 
 
### Type/Category: -- Type and Sub-type

### Version: v0.1
 
### Title: Approve recipe
  
### Description: 
The Content Administrator reviews submitted recipes to ensure they meet the application's quality standards, guidelines, and policies. The approval process includes:

* **Recipe content check:** Verify that the recipe contains complete and accurate information, including ingredients, preparation steps, difficulty and cooking time.
* **Compliance with community guidelines:** Ensure the recipe does not contain inappropriate content, such as offensive language or topics unrelated with the app objectives.
* **Quality assurance:** Check that the recipe is unique and does not duplicate existing content. Ensure it includes clear instructions and an appropriate level of detail for users to follow.
* **Approval Process:** Once the Content Administrator confirms the recipe meets all requirements, they mark it as approved, allowing it to be published on the platform.
* **Rejection and feedback:** If the recipe does not meet the guidelines, the Content Administrator provides feedback to the user, indicating the reasons for rejection and suggesting improvements.

Possibles error that can happens
* **Incomplete information:** The recipe may lack critical details, such as missing ingredients or unclear preparation steps.
* **Violation of guidelines:** The recipe may contain content that violates community standards, leading to rejection.
* **Duplicate recipe:** If the submitted recipe is too similar to an existing one, it may be rejected to avoid redundancy.
* **Technical issues:** Problems with the content management system could prevent the approval process from completing, requiring troubleshooting or system maintenance

### Relations: CFR-2,  UFR-1, UFR-7

### Comments: 
* The approval process should be efficient to minimize delays in publishing user-submitted recipes.
* Content Administrators should have clear guidelines for recipe approval and consistent criteria for evaluating submissions


 --- 

 
### ID: CFR-2
 
### Type/Category: -- Type and Sub-type

### Version: v0.1
 
### Title: Send Notification
  
### Description: 
The Content Administrator sends a notification to the user when their uploaded recipe does not meet the app's guidelines, requesting modifications or suggesting corrections. This process involves:

* **Generate notification:** A notification is created with specific feedback, explaining why the recipe was not approved and what needs to be corrected.
* **Send notification:** The Content Administrator sends the notification to the user via the app's messaging system.

### Relations: CFR-1, UFR-1, MFR-1,  CFR-3 

### Comments: 
* The notification should be clear and constructive, providing specific reasons for rejection and suggesting how to correct the issues.
* A reasonable time frame should be given to the user to modify the recipe. If not addressed within this time, the recipe may be automatically deleted.
* The Content Administrator should be able to track the status of notifications to ensure proper follow-up

 --- 
