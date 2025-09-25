# deploy-configure
deploy and configure niginx web server using ansible

Login into your aws console and ssh your key to the terminal

### run "sudo apt update"
<img width="1118" height="520" alt="Screenshot 2025-09-25 at 4 20 36 pm" src="https://github.com/user-attachments/assets/4d0bc2c0-1d95-41b6-8864-e094cf24187d" />



### run "sudo apt install ansible -y "
<img width="1096" height="456" alt="Screenshot 2025-09-25 at 4 21 11 pm" src="https://github.com/user-attachments/assets/8f09b3fd-3d9e-49e5-a462-a8e78861f4c6" />

### run ansible -version

<img width="1108" height="357" alt="Screenshot 2025-09-25 at 4 22 01 pm" src="https://github.com/user-attachments/assets/8b4552ba-ab87-4bb5-8319-7290d521ef69" />

### run ssh-keygen -t rsa
<img width="1040" height="383" alt="Screenshot 2025-09-25 at 4 25 10 pm" src="https://github.com/user-attachments/assets/8c574064-2aa7-41d2-95b2-4cea8dba22fb" />

### open a file "nano inventory.ini"

<img width="1381" height="896" alt="Screenshot 2025-09-25 at 5 16 36 pm" src="https://github.com/user-attachments/assets/92e339c5-9a7b-4f09-bfbe-b3b3d2b70e26" />

### open a new file "nano install_nginx.yml"

<img width="996" height="823" alt="Screenshot 2025-09-25 at 6 08 45 pm" src="https://github.com/user-attachments/assets/8e786d63-211d-49ad-a737-a78f1613f07a" />

### Open a new file "vim configure_nginx.yml"
<img width="1381" height="896" alt="Screenshot 2025-09-25 at 6 06 44 pm" src="https://github.com/user-attachments/assets/36186309-ee5f-4d34-ac73-56391067c8ba" />

Now run the playbook to install and configure nginx "ansible-playbook -i inventory.ini install_nginx.yml"
<img width="1107" height="235" alt="Screenshot 2025-09-26 at 12 39 31 am" src="https://github.com/user-attachments/assets/204dc785-e6d4-447c-9ce3-c82133d6c287" />

### ansible-playbook -i inventory.ini configure_nginx.yml


<img width="939" height="625" alt="Screenshot 2025-09-26 at 12 42 22 am" src="https://github.com/user-attachments/assets/6436c866-2269-4f91-9bf8-e4d9d33d90ac" />

### Verify nginx is running the tagget server
<img width="921" height="267" alt="Screenshot 2025-09-26 at 12 43 00 am" src="https://github.com/user-attachments/assets/8bd19d5c-5305-4069-90d6-d60357a9079c" />

### run the Local Ip http://44.223.63.0  


<img width="996" height="823" alt="Screenshot 2025-09-26 at 12 51 35 am" src="https://github.com/user-attachments/assets/4024baac-015d-4e8c-9aef-5e7235025310" />

