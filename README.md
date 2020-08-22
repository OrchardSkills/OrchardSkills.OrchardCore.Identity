# OrchardSkills.OrchardCore.Identity

ASP.NET Core Identity with Orchard Core

![itentity-001](https://user-images.githubusercontent.com/59172485/90955719-2f8b0780-e43d-11ea-8582-f592406f6df3.png)

Registration page with Google reCAPTCHA enabled.



![itentity-025](https://user-images.githubusercontent.com/59172485/90955744-3580e880-e43d-11ea-9a5b-c934b0f988d6.png)

Proposed new registration page with social logins OpenID Connect.




![itentity-008](https://user-images.githubusercontent.com/59172485/90955726-31ed6180-e43d-11ea-86dc-96d667f6df97.png)

Received email from admin asking to confirm your account.



![itentity-009](https://user-images.githubusercontent.com/59172485/90955727-31ed6180-e43d-11ea-97c8-bc9dc9c31cd5.png)

Actual Email  to confirm your account. Question: Is there a way to customize Email content?



![itentity-010](https://user-images.githubusercontent.com/59172485/90955728-3285f800-e43d-11ea-98e4-f0b236967b58.png)

Email confirmation page. How do we fix page layout Thank you for confirming your email? Home?




![itentity-013](https://user-images.githubusercontent.com/59172485/90955731-331e8e80-e43d-11ea-85a3-98c658942b89.png)

New registered user logged in.



![itentity-014](https://user-images.githubusercontent.com/59172485/90955732-331e8e80-e43d-11ea-82c5-8c259473ac80.png)

New registered user account page.




![itentity-002](https://user-images.githubusercontent.com/59172485/90955720-30239e00-e43d-11ea-9a27-fb83ba07e407.png)

Log in page with reCAPTCHA enabled. What does the Remember me check dox do?



![itentity-032](https://user-images.githubusercontent.com/59172485/90959534-ed6fbf00-e458-11ea-8321-27af42535210.png)



Proposed a new way to customize the registration and login screens so support TypeScript routines to give immediate feedback of what is needed to the user when they are entering in a new password. They can switch between registration and login easily.




![itentity-026](https://user-images.githubusercontent.com/59172485/90955745-3580e880-e43d-11ea-90fa-1eb5f0acc3c1.png)

Proposed new log in page with social logins OpenID Connect. What does the Remember me check dox do?



![itentity-003](https://user-images.githubusercontent.com/59172485/90955721-30239e00-e43d-11ea-9374-4b8c933c7541.png)

User drop down menu.



![itentity-004](https://user-images.githubusercontent.com/59172485/90955722-30bc3480-e43d-11ea-9aa0-0dea49456453.png)

Change Email page



![itentity-005](https://user-images.githubusercontent.com/59172485/90955723-3154cb00-e43d-11ea-925a-6f6d7a346931.png)

Change password Page.




![itentity-007](https://user-images.githubusercontent.com/59172485/90955725-3154cb00-e43d-11ea-956a-82004da3cc40.png)

Attempt to log in after password has been changed. Could not login with new password. What does the Remember me check dox do?




![itentity-011](https://user-images.githubusercontent.com/59172485/90955729-3285f800-e43d-11ea-98ec-30aaf4d732de.png)

Change Email page.



![itentity-012](https://user-images.githubusercontent.com/59172485/90955730-3285f800-e43d-11ea-9fa9-3151c85e4b2f.png)

Email changed page. How do we fix page layout Thank you for changing your email.



![itentity-015](https://user-images.githubusercontent.com/59172485/90955733-331e8e80-e43d-11ea-877a-065ff0dd07d1.png)

After email changed. Attempt to log in fails. Invalid login attempt. What does the Remember me check dox do?



![itentity-016](https://user-images.githubusercontent.com/59172485/90955734-33b72500-e43d-11ea-9896-2a80de1402ee.png)

Forgot your password issue when hovering over it with mouse. It fades away. What does the Remember me check dox do?



![itentity-017](https://user-images.githubusercontent.com/59172485/90955735-33b72500-e43d-11ea-91a1-e0395cbcfc41.png)

Forgot password page. How do we fix page layout.



![itentity-018](https://user-images.githubusercontent.com/59172485/90955736-33b72500-e43d-11ea-801b-63d346c215c4.png)

Forgot password confirmation page. How do we fix page layout?



![itentity-019](https://user-images.githubusercontent.com/59172485/90955737-344fbb80-e43d-11ea-8a1c-4f66eb251383.png)

Email received Reset your password.



![itentity-020](https://user-images.githubusercontent.com/59172485/90955738-344fbb80-e43d-11ea-926f-f3d4542b1cc6.png)

Actual email Reset your password. Question: Is there a way to customize Email content?



![itentity-021](https://user-images.githubusercontent.com/59172485/90955740-34e85200-e43d-11ea-8b67-06389ee49d8d.png)

Reset password page. Clicked on Please "click here" to change your password link from email.



![itentity-022](https://user-images.githubusercontent.com/59172485/90955741-34e85200-e43d-11ea-9f94-74b6d1e773e7.png)

Reset Password confirmation page. How do we fix page layout?

![itentity-027](https://user-images.githubusercontent.com/59172485/90958438-cfeb2700-e451-11ea-88b4-5f455b1f2f8e.png)

Email Settings Page


![itentity-028](https://user-images.githubusercontent.com/59172485/90958439-d083bd80-e451-11ea-96a9-2eb8dafc2690.png)

Login Page Settings How to Use a script to set user roles based on external provider claims.



![itentity-029](https://user-images.githubusercontent.com/59172485/90958441-d083bd80-e451-11ea-878c-b305f5450860.png)

reCAPTCHA Page Settings



![itentity-030](https://user-images.githubusercontent.com/59172485/90958442-d11c5400-e451-11ea-94f6-cbaf6cc56262.png)

Registration Settings Page Question: How to Use a script to generate userName based on external provider claims.



![itentity-031](https://user-images.githubusercontent.com/59172485/90958443-d11c5400-e451-11ea-9645-6e8c084ebc02.png)

Reset Password Settings Page



Recipe settings User

```
    {
      "name": "Settings",
      "ChangeEmailSettings": {
        "AllowChangeEmail": true
      },
      "LoginSettings": {
        "UseSiteTheme": true,
        "UseExternalProviderIfOnlyOneDefined": false,
        "DisableLocalLogin": false,
        "UseScriptToSyncRoles": false,
        "SyncRolesScript": null
      },
      "RegistrationSettings": {
        "UsersCanRegister": 1,
        "UsersMustValidateEmail": true,
        "UseSiteTheme": true,
        "NoPasswordForExternalUsers": false,
        "NoUsernameForExternalUsers": false,
        "NoEmailForExternalUsers": false,
        "UseScriptToGenerateUsername": false,
        "GenerateUsernameScript": null
      },
      "ResetPasswordSettings": {
        "AllowResetPassword": true,
        "UseSiteTheme": true
      },
      "ReCaptchaSettings": {
        "SiteKey": "6LcXMb0ZAAAAADh2OfV7wG88aPXSfZO4JgLBRA7W",
        "SecretKey": "6LcXMb0ZAAAAAJXyGfKHEAoxCnOf1bqe1g6RXgEZ",
        "ReCaptchaScriptUri": "https://www.google.com/recaptcha/api.js",
        "ReCaptchaApiUri": "https://www.google.com/recaptcha/api/",
        "DetectionThreshold": 5
      }
    },
```

