# firebase_authentication_android
This is an anpp that uses firebase to authenticate a user via their phone number. MainActivity -> VerifyPhoneActivity ->ProfileActivity

Main Activity: gets user's phone number and passes it to the next activity (VerifyPhoneActivity)
VerifyPhoneActivity: takes passed phone number and sends code for authentication. This auto detects message or the user can enter in the code they received
ProfileActivity: displays after authentication is conpleted
