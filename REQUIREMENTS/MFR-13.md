
### ID: MFR-13
 
### Version: v2.1
 
### Title: User Verification Management
  
### Description: 
This requirement details the process of verifying newly registered users. Once a user completes the registration form, the system will automatically send a verification email to the user's provided email address. The email contains a verification link that the user must click to confirm their account. Additionally, an Administration Manager can manually verify users if necessary, especially in cases where users encounter issues with the automatic verification process.

### Relations: 
[UFR-1](https://github.com/carmensat/RECIPE-ROULETTE/blob/main/REQUIREMENTS/UFR-1.md), 
[UFR-2](https://github.com/carmensat/RECIPE-ROULETTE/blob/main/REQUIREMENTS/UFR-2.md), and
[CFR-15](https://github.com/carmensat/RECIPE-ROULETTE/blob/main/REQUIREMENTS/CFR-15.md).

### Comments: 
* The verification email should include a unique link that expires after a certain period (e.g., 24 hours).
* If the user does not verify their account within the given time frame, they should be able to request a new verification email.
* The Administration Manager should have a dashboard to view unverified accounts and manually send verification emails or approve users if needed.
* Consider using third-party services like SendGrid or Amazon SES for reliable email delivery.


