Q No.1 What are the different protocols present in the captured traffic file?
<img width="617" height="481" alt="image" src="https://github.com/user-attachments/assets/d7ea9c4a-c60a-482b-89e4-44b77ad5c471" />
Q No.2 It appears that the attacker is attempting to brute force the user's FTP password. Can you find any evidence of a correct password, and if so, what is it?
<img width="1070" height="605" alt="image" src="https://github.com/user-attachments/assets/2c3b617f-1bda-4707-b14e-359acc0898ad" />
Q No.3 What additional information was the attacker able to extract from the user's FTP account?
<img width="1059" height="554" alt="image" src="https://github.com/user-attachments/assets/1cff2110-bc96-4cad-966c-10d80f7fb9bf" />
<img width="1054" height="523" alt="image" src="https://github.com/user-attachments/assets/250a1b3e-488c-4d17-be08-74a25e8eda12" />
As you can see he used the command la and listed the contents in the directory.
Q No.4 What actions did the attacker take with the information obtained from the user's FTP account?
<img width="1075" height="605" alt="image" src="https://github.com/user-attachments/assets/0e39821b-d920-43e5-88de-e686348b1da4" />
He extracted the credential.txt file and it contained the username and password which is very sensitive.
Q No.5 What's the root account password?
<img width="1038" height="300" alt="image" src="https://github.com/user-attachments/assets/566f2162-2d4d-4a64-8f37-26a71165b546" />
The root password is 1amgr000000t!@#$.
Q No.6 Can you identify the packet numbers in which the attacker exploited the Remote Code Execution vulnerability to gain access to the system? What was the exact payload used by the attacker?

