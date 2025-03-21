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
   ![Screenshot 2025-03-21 214742](https://github.com/user-attachments/assets/981cc1c8-a416-43e6-a8ed-6f94ac1900ee)
   ![Screenshot 2025-03-21 214801](https://github.com/user-attachments/assets/4b011824-222c-4c7f-8487-c706f19c6fe3)


   
3. chmod Command -> (a)Give execute permission to the user: chmod u+x file.txt
   (b)Remove write permission for others: chmod o-w file.txt
   (c)Give read and execute permission to the group: chmod g+rx file.txt
   (d)Set specific permissions: chmod u=rwx,g=rx,o=r file.txt
   (e)Set permissions to rwxr-xr-- using octal mode: chmod 754 file.txt
   (f)Recursive Change of Permissions: chmod -R 755 /path/to/directory
   (g)Change permissions based on existing files: chmod --reference=ref_file.txt target_file.txt
