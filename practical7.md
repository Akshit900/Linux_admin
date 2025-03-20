1. chown Command -> (a)Change the owner of a file: sudo chown user1 file.txt
   (b)Change the owner and group of a file: sudo chown user1:usergroup file.txt
   (c)Change only the group: sudo chown :usergroup file.txt
   (d)Change ownership recursively (for directories): sudo chown -R user1:usergroup /path/to/directory
   (e)Transfer ownership to root: sudo chown root file.txt
   (f)Use --from to change from a specific owner: sudo chown --from=current_owner new_owner file.txt
2. chmod Command -> (a)Give execute permission to the user: chmod u+x file.txt
   (b)Remove write permission for others: chmod o-w file.txt
   (c)Give read and execute permission to the group: chmod g+rx file.txt
   (d)Set specific permissions: chmod u=rwx,g=rx,o=r file.txt
   (e)Set permissions to rwxr-xr-- using octal mode: chmod 754 file.txt
   (f)Recursive Change of Permissions: chmod -R 755 /path/to/directory
   (g)Change permissions based on existing files: chmod --reference=ref_file.txt target_file.txt
