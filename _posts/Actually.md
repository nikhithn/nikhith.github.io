# Actually...

## *"Authorization = credentials"*

A fundamental concept in identity and access is the distinction between authentication and authorization.  Authentication is the process by with a user confirms identity -- confirms that the user is the identity that she/he claims to be. Often, this takes the form of supplying valid credentials, username and password.  

Authorization, on the other hand, is verifying that the user has permission or access to particular protected resource.  This is often downstream of authentication; after the identity of the user is confirmed (or is assumed to be anonymous), the user's permissions are compared to the requirements of the protected resource to determine if they should be granted access.  
