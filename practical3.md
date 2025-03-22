1. Open the editing_final_lab.txt file in Vim and Nano: -> VIM- vim editing_final_lab.txt NANO- nano editing_final_lab.txt

   ![Screenshot 2025-03-20 154839](https://github.com/user-attachments/assets/62571122-2537-4d41-86f4-5a795344805a)

   ![Screenshot 2025-03-20 155049](https://github.com/user-attachments/assets/5aea8824-63dd-4286-91ad-528717306d05)


   ![Screenshot 2025-03-20 160537](https://github.com/user-attachments/assets/92a55465-7024-4e58-9463-eb489ed04326)

2. Use the lab_file shell variable: -> lab_file="editing_final_lab.txt" vim $lab_file

   ![Screenshot 2025-03-20 160714](https://github.com/user-attachments/assets/712b46fd-304b-4ce6-9ce6-8e1f431bdb16)

3. Enter visual mode in Vim: -> Open Vim. Press v to enter visual mode.
   ![image](https://github.com/user-attachments/assets/fe9b24df-c748-420f-90e1-6dabea3866c2)

4. Remove the last seven characters from the first line: -> Press ^ (caret) to go to the beginning of the line. Press v to start selecting characters. Move to the end of the line using $. Press d7 to delete the last 7 characters.

5. Preserve only the first four characters of the first column: -> Go to the beginning of the line using 0. Press v and move to the 4th character using l (right arrow). Press d to delete everything after the 4th character.

6. Save and exit: -> :wq 


