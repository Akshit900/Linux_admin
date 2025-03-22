1. Shell Script to Print System Information -> (a)Create a file named system_info.sh:
   ![Screenshot 2025-03-22 141854](https://github.com/user-attachments/assets/64c42849-d5ad-4368-9de6-ad9dde31bdaa)

(b)Make the script executable: chmod +x system_info.sh

(c)Run the script: ./system_info.sh
   ![Screenshot 2025-03-22 141730](https://github.com/user-attachments/assets/4737c47f-cd58-4605-9591-aa37aa6dd5f3)

2. Shell Script to Perform Basic Mathematical Calculation -> (a)Create a file named calc.sh:
   ![Screenshot 2025-03-22 143533](https://github.com/user-attachments/assets/dab20c5a-e989-4e27-8d33-cb9432449cd2)

   (b)Make the script executable: chmod +x calc.sh

   (c)Run the script: ./calc.sh
      ![Screenshot 2025-03-22 143509](https://github.com/user-attachments/assets/eb1d0ce5-996f-44e4-b191-090b03129f7c)

3. Use Redirection Operators to Store Output of Commands -> (a)Redirect stdout to a file: ls > output.txt
   ![Screenshot 2025-03-22 143628](https://github.com/user-attachments/assets/5b144bd9-ad74-412b-ba8f-ea6ce4402019)
   
   (b)Append output to an existing file: date >> output.txt
      ![Screenshot 2025-03-22 143652](https://github.com/user-attachments/assets/8120c4fb-4a53-4648-9c7b-5ad69e72a6d6)
      ![Screenshot 2025-03-22 143921](https://github.com/user-attachments/assets/d8e6cbc0-b098-4da4-9717-2931680443ee)

   (c)Redirect stderr to a file: ls nonexistentfile 2> error.txt
      ![Screenshot 2025-03-22 144007](https://github.com/user-attachments/assets/aa0103eb-05b0-4ec4-a50f-cdd16b30ad0c)

   (d)Redirect both stdout and stderr to a file: ls . nonexistentfile &> all_output.txt
      ![Screenshot 2025-03-22 144110](https://github.com/user-attachments/assets/3b32f6cc-f920-45bd-b590-4b9cb5b7324c)
      ![Screenshot 2025-03-22 144226](https://github.com/user-attachments/assets/10ff0354-1a31-46e7-b92d-106c49278f0f)
   
   (e)Pipe output to another command: cat file.txt | grep "keyword"
      ![Screenshot 2025-03-22 144322](https://github.com/user-attachments/assets/f059be18-aac5-4bc6-9ce5-1a1c911f4124)

   
   
