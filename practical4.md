1. Create the /home/consultants directory: -> sudo mkdir /home/consultants
![Screenshot 2025-03-20 161047](https://github.com/user-attachments/assets/061893c0-c939-4437-baa8-a9dd7b610c73)
2. Add write permission to the consultants group (symbolic method): -> sudo chmod g+w /home/consultants
![Screenshot 2025-03-20 161150](https://github.com/user-attachments/assets/46795a12-e054-4680-9608-36ea13302d13)
3. Forbid others from accessing the /home/consultants directory (octal method): -> sudo chmod 750 /home/consultants
![Screenshot 2025-03-20 161232](https://github.com/user-attachments/assets/61515758-2246-4337-87c2-0257e7863913)
![Screenshot 2025-03-20 161319](https://github.com/user-attachments/assets/6e8738aa-09aa-410a-ae37-668dec2d90a9)
4. Change the default umask for the operator1 user: -> (a)Open the user’s .bashrc or .profile file: sudo nano /home/ubuntu/.bashrc

   (b)Add the following line to set the umask: umask 0074
   ![Screenshot 2025-03-20 162002](https://github.com/user-attachments/assets/fb7c8478-9319-4be1-a317-be8f5c8935c1)
   ![Screenshot 2025-03-20 162418](https://github.com/user-attachments/assets/0d9e9eb3-1edb-407a-9b77-c1d01e4327ac)

5. Confirm the umask: -> su - ubuntu umask
![Screenshot 2025-03-20 163132](https://github.com/user-attachments/assets/f7533d56-0941-4524-8bca-d97dc635ae30)
