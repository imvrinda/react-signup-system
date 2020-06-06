# react-signup-system

React - Email Sign Up with Verification, Authentication & Forgot Password


About:

- Email sign up and verification
- Authentication and role based authorization with support for two roles (User & Admin)
- Forgot password and reset password functionality
- View and update my profile section
- Admin section with sub section for managing all users (restricted to the Admin role)

There are no users registered in the application by default, in order to login you must first register and verify an account. 
The fake backend displays "email" messages on screen because it can't send real emails, 
so after registration a "verification email" is displayed with a link to verify the account just registered, 
click the link to verify the account and login to the app.

The first user registered is assigned to the Admin role and subsequent users are assigned to the regular User role.
Admins can access the admin section and manage all users, while regular users can only update their own profile.
