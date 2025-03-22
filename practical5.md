1. ps Command -> (a)Display all running processes: ps aux

   ![Screenshot 2025-03-20 163210](https://github.com/user-attachments/assets/7c761fcf-b346-4c18-ab5b-2cd811ed4569)

   (b)Show processes for the current terminal session: ps

   ![Screenshot 2025-03-20 163230](https://github.com/user-attachments/assets/88fa5fd8-71c2-442e-a551-e7f819b989d7)

   (c)Display a process tree: ps -e --forest


   ![Screenshot 2025-03-20 163421](https://github.com/user-attachments/assets/f7b37c96-1f93-45fe-9613-603f64a961f5)

   (d)Filter by process name: ps -C firefox

   ![Screenshot 2025-03-20 163509](https://github.com/user-attachments/assets/eec74137-851d-4dc1-8e46-d166e0e5abcf)

   (f)Show detailed information of a specific process: ps -p 1234 -o pid,ppid,cmd,%mem,%cpu

   ![Screenshot 2025-03-20 163642](https://github.com/user-attachments/assets/e9603d1e-7573-4861-9ac9-314eaaaf26ac)

3. kill Command -> (a)Find the PID: ps aux | grep firefox

   (b)Kill a process by PID: kill 1234

   (c)Force kill a process: kill -9 1234

   (d)Kill by process name: killall firefox

3. top Command -> top Sort by memory usage: Press M Sort by CPU usage: Press P Kill a process: Press k → Enter the PID Exit top: Press q

    ![Screenshot 2025-03-20 163730](https://github.com/user-attachments/assets/ea38402a-c0f6-4d76-ba3e-71f8418b642f)

5. apt-get Command -> (a)Update package list: sudo apt-get update

   ![Screenshot 2025-03-20 163944](https://github.com/user-attachments/assets/dc7c49ea-9f9c-4357-8bcd-60d15b6070c8)


   (b)Upgrade installed packages: sudo apt-get upgrade

    ![image](https://github.com/user-attachments/assets/6de30ffc-ccbc-47aa-aa77-51f16195cd3a)


    (c)Install a package: sudo apt-get install vim

   ![Screenshot 2025-03-20 164910](https://github.com/user-attachments/assets/596e8593-5cce-456e-b9ca-10732f99662a)


   (d)Remove a package: sudo apt-get remove vim

   ![Screenshot 2025-03-20 165128](https://github.com/user-attachments/assets/c8e33130-7aaf-4f5c-ad0f-765b3d012970)

   (e)Remove package along with configuration files: sudo apt-get purge vim

   ![Screenshot 2025-03-20 165214](https://github.com/user-attachments/assets/10a421cf-863f-4446-88c9-ec76441637fc)


   (f)Clean up unused packages: sudo apt-get autoremove

   ![Screenshot 2025-03-20 165310](https://github.com/user-attachments/assets/7a0070fa-751f-4392-b8ea-186c9606cefc)

   (g)Clean package cache: sudo apt-get clean

   ![Screenshot 2025-03-20 165335](https://github.com/user-attachments/assets/e4d5741f-f462-4028-a5dc-b797ecc73715)


