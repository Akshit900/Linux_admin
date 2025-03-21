1. chown Command -> (a)Change the owner of a file: sudo chown user1 file.txt
   ![Screenshot 2025-03-21 213948](https://github.com/user-attachments/assets/58635bcb-bdf4-4279-87db-5fb2a8474445)

   (b)Change the owner and group of a file: sudo chown user1:usergroup file.txt
   ![Screenshot 2025-03-21 214111](https://github.com/user-attachments/assets/75f27231-e00b-43b7-989b-7b3e9bebeec0)

   (c)Change only the group: sudo chown :usergroup file.txt
   ![Screenshot 2025-03-21 214325](https://github.com/user-attachments/assets/c5adf624-2d95-4717-b3af-753da4e3adfd)

   (d)Change ownership recursively (for directories): sudo chown -R user1:usergroup 
      /path/to/directory
   ![Screenshot 2025-03-21 214418](https://github.com/user-attachments/assets/4417fa4c-64aa-4e9b-adbc-6d796a9775ac)

   (e)Transfer ownership to root: sudo chown root file.txt
   ![Screenshot 2025-03-21 214503](https://github.com/user-attachments/assets/880a96c0-c9b8-4471-a282-040300775ca3)

   (f)Use --from to change from a specific owner: sudo chown --from=current_owner new_owner 
      file.txt
      ![Screenshot 2025-03-21 215649](https://github.com/user-attachments/assets/45fa71a6-c7df-4f45-be97-deac64b64a34)



   
2. chmod Command -> (a)Give execute permission to the user: chmod u+x file.txt
   ![Screenshot 2025-03-21 220320](https://github.com/user-attachments/assets/9926e762-038c-4c82-b858-71cd89782f6a)

   (b)Remove write permission for others: chmod o-w file.txt
   ![Screenshot 2025-03-21 220413](https://github.com/user-attachments/assets/9c4d2d46-42e5-487b-accc-16cb5bf35fe5)

   (c)Give read and execute permission to the group: chmod g+rx file.txt
   ![Screenshot 2025-03-21 220448](https://github.com/user-attachments/assets/0a784775-ec7d-4589-8dc1-2b4f494e71f3)

   (d)Set specific permissions: chmod u=rwx,g=rx,o=r file.txt
   ![Screenshot 2025-03-21 220539](https://github.com/user-attachments/assets/9fd10337-8ae9-41a0-af52-abc82d55177e)

   (e)Set permissions to rwxr-xr-- using octal mode: chmod 754 file.txt
   ![Screenshot 2025-03-21 221126](https://github.com/user-attachments/assets/2825d7c2-802f-4b62-9b6d-2c5a28f9c537)

   (f)Recursive Change of Permissions: chmod -R 755 /path/to/directory
   ![Screenshot 2025-03-21 221859](https://github.com/user-attachments/assets/2dee9235-77b6-4305-9738-a338357852d6)

   (g)Change permissions based on existing files: chmod --reference=ref_file.txt target_file.txt
   ![Screenshot 2025-03-21 222003](https://github.com/user-attachments/assets/657eb692-157f-46a5-a524-96f61d174fe1)

