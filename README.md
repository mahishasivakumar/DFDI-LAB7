# EXP 7 :USING JOHN THE RIPPER FOR PASSWORD CRACKING

## AIM:
To crack password hashes using John the Ripper in Kali Linux.

## EQUIPMENTS REQUIRED:
●	Hardware: PCs

```
Register Number: 212222040095
Name: Mahisha S
```

## DESIGN STEPS:
### Step 1:
Install John the Ripper in Kali linux

### Step 2:
Prepare the password hash file (e.g., using unshadow for Linux password and shadow files).

### Step 3:
Use John the Ripper to crack the hashes

## PROCEDURE:
### Step 1: Create a Text File

  •	Right-click on the Desktop and choose Create Document → Empty Document.
  
  •	Name the file: mahisha.txt.

  ![Screenshot 2025-04-22 183028](https://github.com/user-attachments/assets/ad61c866-4f83-4770-bb32-e743d93c4a92)


  •	Open it and type:

  ![Screenshot 2025-04-22 183101](https://github.com/user-attachments/assets/c946133f-3bdc-4c09-ae5d-57b128904e8a)


  •	Save and close the file.

### Step 2: Create a Password-Protected ZIP File

  •	Right-click on praveen.txt → Create Archive.
  
  ![Screenshot 2025-04-22 183144](https://github.com/user-attachments/assets/729f6455-927c-4680-8002-a02824bee4d9)


  •	Select .zip format.
  
  •	Click Other Options, set a password (e.g., 1234), then click Create.

  ![Screenshot 2025-04-22 183230](https://github.com/user-attachments/assets/682b5157-9460-47ab-a03f-5963557d4ae8)


  •	A file named praveen.txt.zip will appear.

### Step 3: Open John the Ripper Terminal in Kali Linux

  •	Click on the Kali menu or press the Super (Windows) key.
  
  •	Search for “john” and click it — this opens the terminal with John the Ripper installed.

  ![Screenshot 2025-04-22 183303](https://github.com/user-attachments/assets/121b6a0c-4b81-431c-92ed-d47cbb898636)


  •	Or simply open a Terminal from the dock or desktop.

### Step 4: Navigate to the File Location

  •	In the terminal, switch to the Desktop where the ZIP file is located:
  
  ![Screenshot 2025-04-22 183331](https://github.com/user-attachments/assets/dc5374d4-eb43-4713-83f1-c571cfb0b3cf)


### Step 5: Confirm the ZIP File is Present

  •	Run: “ls” command
  
  ![Screenshot 2025-04-22 183350](https://github.com/user-attachments/assets/e2501125-82fb-4170-9987-a84261de9fa0)


  •	You should see praveen.txt.zip listed.

### Step 6: Generate Hash Using zip2john

  •	Execute:
  
  ![Screenshot 2025-04-22 183429](https://github.com/user-attachments/assets/b2fb4d69-5070-4d1b-bc0b-ec8f247ce229)


### Step 7: Verify the Hash File (Optional)
  •	Open hash.txt to ensure it contains the hash line.
  
  ![Screenshot 2025-04-22 183451](https://github.com/user-attachments/assets/4bf6c35c-66cf-4d36-a489-12c6830ce7f5)


### Step 8: Start Cracking the Password
  •	Run:
  
  ![Screenshot 2025-04-22 183552](https://github.com/user-attachments/assets/f1afb549-b56e-498d-8ff3-deb29854ba22)


## OUTPUT:View the Cracked Password
  • After cracking is complete, reveal the password using:
  
  ![image](https://github.com/user-attachments/assets/d93fe2be-f483-4326-beca-31c7b6affb85)


  •	The terminal will display the filename and its cracked password.


## RESULT:
The password hashes were successfully cracked using John the Ripper.

