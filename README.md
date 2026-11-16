# networkwalks-B084-week2-Cybersecurity-Project-Module2-Password-Cracking-with-JTR&NW-Tools-v1
This project demonstrates password security testing using John the Ripper (JTR) and Johnny GUI. The task involves extracting a password hash from an encrypted PDF, loading it into Johnny, performing a password-cracking attack, and verifying the recovered password.

1. Install John the Ripper: Download and install JTR on Windows or use Kali Linux.
  https://www.openwall.com/john/ or https://distro.ibiblio.org/openwall/projects/john/1.9.0/
<img width="882" height="498" alt="image" src="https://github.com/user-attachments/assets/e727d4f6-c568-485f-9e3d-78a921dbd918" />

2. Install Johnny GUI: Install and configure Johnny with john.exe.
https://openwall.info/wiki/john/johnny
<img width="131" height="171" alt="image" src="https://github.com/user-attachments/assets/9cec516e-8476-41f3-bc5d-d9a84db0de94" />

4.Select John.exe:
   <img width="1192" height="557" alt="image" src="https://github.com/user-attachments/assets/cef14946-35b2-4a35-8af9-014aa3814f2e" />

3. Click on settings & browse:
   <img width="882" height="692" alt="Screenshot 2026-11-16 124231" src="https://github.com/user-attachments/assets/f755762a-1143-4e42-9936-b5b0ca10b5dc" />

4. Download Encrypted PDF: Use the provided password-protected PDF.
   <img width="1495" height="636" alt="Screenshot 2026-11-16 124332" src="https://github.com/user-attachments/assets/db42431a-6353-4868-99ea-a85197600b83" />
   
5. Extract PDF Hash: Extract the PDF hash using a PDF hash extraction tool.
 https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php
   <img width="1796" height="966" alt="Screenshot 2026-11-16 124450" src="https://github.com/user-attachments/assets/af493737-fb9e-46a4-83cf-92627704aedf" />

6.Select & copy the hash value
7.Save Hash: Copy the extracted hash into hash1.txt.(notepad)
8.Load Hash in Johnny: Open Johnny and import the hash file and click on start new attack.
<img width="1917" height="1020" alt="Screenshot 2026-11-16 125003" src="https://github.com/user-attachments/assets/cef6ecd9-3850-4c96-8f42-061dcf8adfea" />

9.Recover Password: Check the recovered password.
10.Verify Password: Open the protected PDF using the recovered password.
<img width="585" height="821" alt="Screenshot 2026-11-16 125142" src="https://github.com/user-attachments/assets/1fb2b25e-5862-424c-8c40-04165627c11e" />



**-------------------------------------------------------------------------using NW tools----------------------------------------------------------------------**
STEP 1
Download the encrypted PDF file (My Locked PDF1.pdf) to your laptop from the lab page:
https://networkwalks.com/project-task-lab-password-cracking-with-networkwalks-tools/

STEP 2
Open the Networkwalks Hash Calculator in your web browser:
https://networkwalks.com/hash-calculator/
<img width="1822" height="943" alt="Screenshot 2026-11-16 125828" src="https://github.com/user-attachments/assets/def7ea22-54b8-44a1-b55e-048f0da7ed27" />

STEP 3
Upload the locked PDF file to the Hash Calculator. The tool will read the file and give you the hash
value that starts with $pdf$...
<img width="1891" height="965" alt="Screenshot 2026-11-16 125921" src="https://github.com/user-attachments/assets/23cf18cd-f579-45a6-84a4-3947638680e4" />

STEP 4
Copy the full hash value.
Note: Copy the complete hash starting from $pdf$. Do not miss any part of it.
<img width="1816" height="927" alt="Screenshot 2026-11-16 125905" src="https://github.com/user-attachments/assets/9ff1b138-ae88-4620-8a40-22ac6c68ab99" />

STEP 5
Open the Networkwalks Password Cracker in your web browser:
https://networkwalks.com/password-cracker/
<img width="1893" height="956" alt="image" src="https://github.com/user-attachments/assets/09744632-ce26-4d79-8948-b68344c3c866" />

STEP 7
Wait for the tool to finish. The cracked password will be shown on the screen
Note: The time taken depends on how simple or complex the password is.
<img width="1891" height="965" alt="Screenshot 2026-11-16 125921" src="https://github.com/user-attachments/assets/1300f1df-2f48-4d87-882e-e3e29197446d" />
<img width="1915" height="938" alt="image" src="https://github.com/user-attachments/assets/cee4dc3f-b5de-4fd9-a8a4-ae5c6aa9a91a" />

STEP 8
Open the locked PDF file and enter the cracked password.
Enter password1 (which you have just cracked):
<img width="1902" height="862" alt="image" src="https://github.com/user-attachments/assets/d04c39b8-5f29-420c-971d-636e48054463" />

STEP 9
Your PDF file will open. You have completed the lab
<img width="730" height="648" alt="Screenshot 2026-11-16 125943" src="https://github.com/user-attachments/assets/d67631ca-4950-4d2b-910e-3806bde1ba0b" />
