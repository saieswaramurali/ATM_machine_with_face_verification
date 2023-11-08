# ATM_machine_with_face_verification
ATM machine code with face verification

a basic code using python for enabling multi-step-verfication on atm machine using OTP (one time password) and FACE-RECOGNITION 
this is a python program allows you to create or login into an account and enable you to access some functions like depositing the cash, 
withdrawing the cash, viewing the balance etc., 

don't forget to add the known and Unknown files on your environment 
to do the face verification 

it generates otp using twilio api servies, 
replace the SSID and authentication token in the code by your login creadentials obtain from your
twilio account. 
thus you can generate a otp verification 
if someone wants to withdraw cash above a thershold limit of 15,000 
it verifies client's face using face_verification library 
this code uses a dummy list which has the encoding for the images assuming the unknown list is the image captured 
at the moment of login when the client withdraws the cash. 
you can replace this with the webcam feed of yours to get a full fledged thing. 

