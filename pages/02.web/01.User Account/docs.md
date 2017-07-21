---
title: User Account
taxonomy:
    category: docs
process:
	twig: true
---

## Account Registration

1. Fill the registration form on the [registration page](https://www.smir.ch/Account/Register). Select the appropriate Research Unit. If you need to register a Research Unit, please follow the step in [research unit registration section](#research-unit-registration).
2. Accept the [End User License Agreement](https://www.smir.ch/Home/TermsAndConditions) using the checkbox
3. Complete the Captcha
4. Submit 
5. The Administrator of the Research Unit receive your request and has to process it. This is a manual processes. Please allow up to 7 days for this step. 
6. You will receive an email with your login credentials consisting of the email used for registration and an initial password. Follow the instruction in the [password change section](#password-change) to change the initial password![smir-registration-user](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-registration-user.png)

## Account setup

Go to [MySMIR > Account & Settings](www.smir.ch/MyDB/Profile) to check your profile. Please consider adding a recovery email.

- Title
- Firstname
- Lastname
- Recovery email

## Account deletion

For now, use the [ticket system](https://tickets.smir.ch) to request a deletion: Include the exact same information from your profile in the ticket. 

- Title
- Firstname
- Lastname
- Email
- Recovery email
- Username

## I can't login to my account

### Locked account

Description:    After 5 failed login atemps, your account will be locked for 10 minutes 

Solution:    You can try again after waiting 10 minutes

### Disabled account

Description:  In case of missbehavior or similar reasons, the SMIR team can disable account. 

Solution:  Contact us using our [ticket system](https://tickets.smir.ch)


Description: You have lost your last Research Unit membership

Solution:  Contact us using our [ticket system](https://ticktets.smir.ch)

### Invalid credentials

Description: I forgot my password 

Solution:  You can [reset your password](https://www.smir.ch/Account/LostPassword). Read the [password reset section](#password-reset) for instructions.

## Password change

The password can be changed on the [MySMIR > Account & Settings](www.smir.ch/MyDB/Profile) page. See the [password policy section](#password-policy) to create a valid password.

## Password policy

The password has to fullfil these criterias to be valid:

- Length must be between 8 and 12 characters
- It must contain 1 number (0-9)
- It must contain 1 lower case character
- It must contain 1 upper case character
- It must contain 1 special character `( ? } { $ - . , ; : ! ] [ )`


## Password reset

1. Use the [password recovery page](https://www.smir.ch/Account/LostPassword) to reset your lost password.
2. A link to create a new password will be sent to both the registration email and the recovery email. Follow this link to create a new password according to the [password policy](#password-policy)