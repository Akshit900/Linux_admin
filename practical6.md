1. Create the operator1 user: -> sudo useradd -m operator1
![Screenshot 2025-03-20 165429](https://github.com/user-attachments/assets/79e30cb0-e1b9-4e23-9b7d-90b6091284dd)

2. Confirm that operator1 exists: -> cat /etc/passwd | grep operator1
![Screenshot 2025-03-20 165510](https://github.com/user-attachments/assets/62e8e4e2-5650-4c3c-b79a-31ea5a7e2d37)

3. Set the password for operator1: -> sudo passwd operator1
![Screenshot 2025-03-20 165555](https://github.com/user-attachments/assets/c58524c4-e488-47f9-ac3e-d6f3482ca4d4)

4. Create operator2 and operator3 users: -> sudo useradd -m operator2 sudo passwd operator2 sudo useradd -m operator3 sudo passwd operator3
![Screenshot 2025-03-20 165835](https://github.com/user-attachments/assets/007978eb-feda-4297-9aa6-111f1454b3e9)

5. Update the comment for operator1 using usermod -c: -> sudo usermod -c "System Operator 1" operator1
![Screenshot 2025-03-20 165935](https://github.com/user-attachments/assets/c69831f5-4e35-4b79-a374-1e9c32876157)

6. Remove the operator3 user: -> (a)To delete operator3 without removing the home directory: sudo userdel operator3
![Screenshot 2025-03-20 170002](https://github.com/user-attachments/assets/769a0147-8f91-455a-90aa-73b68129066f)

(b)To delete operator3 and its home directory: sudo userdel -r operator3
![Screenshot 2025-03-20 170056](https://github.com/user-attachments/assets/0a5381c9-2b70-4817-ade0-c65e52bedc66)
