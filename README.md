# node-auth

This application has the following features:

- Local account logins and signups (using passport-local)
- Facebook logins and registration (using passport-facebook)
- Twitter logins and registration (using passport-twitter)
- Google+ logins and registration (using oauth with passport-google-oauth)
- Require login for certain routes/sections of your application
- Creating a password hash for local accounts (using bcrypt-nodejs)
- Displaying error messages (using flash with connect-flash. required since express 3.x)
- Linking all social accounts under one user account
- Allowing a user to unlink a specific social account
