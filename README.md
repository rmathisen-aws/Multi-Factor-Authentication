# Multi-Factor Authentication

### Introduction:
AWS Multi-Factor Authentication (MFA) is a simple best practice that adds an extra layer of protection on top of your user name and password. With MFA enabled, when a user signs in to an AWS Management Console, they will be prompted for their user name and password (the first factor—what they know), as well as for an authentication code from their AWS MFA device (the second factor—what they have). Taken together, these multiple factors provide increased security for your AWS account settings and resources.

### Summary:
In this demo, we'll be setting up Multi-Factor Authentication for the User that's currently logged in. The Authentication will be through an Authenticator app which is installed on your mobile device or computer, and we will connect our User to that device. We will test the MFA to confirm that it is properly working.

Account dropdown → My Security Credentials 
AWS IAM Credentials tab → scroll down to Multi-Factor Authentication → Assign MFA device

Virtual MFA Device

Connect Device to Account using QR Code

Test MFA by logging out & logging back in
