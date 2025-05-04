# Using-tools-like-John-the-Ripper-for-password-cracking
## AIM:
To crack password hashes using John the Ripper in Kali Linux.

## DESIGN STEPS:
### Step 1:
Install John the Ripper using the command:

### Step 2:
Prepare the password hash file (e.g., using unshadow for Linux password and shadow files).


### Step 3:
Use John the Ripper to crack the hashes:

## PROCEDURE:

# Step 1: Create a Text File
• Right-click on the Desktop and choose Create Document → Empty Document.

• Name the file: praveen.txt.

```
![1](https://github.com/user-attachments/assets/469b226c-6b78-4e74-bdf5-82a4c5536e9f)
```
• Open it and type:
![image](https://github.com/user-attachments/assets/7475dfea-72c5-4bf6-beb4-95d295c14a69)

• Save and close the file.

# Step 2: Create a Password-Protected ZIP File

• Right-click on praveen.txt → Create Archive.

![image](https://github.com/user-attachments/assets/75cddf2a-75c1-4823-b298-234b58e39ef1)

• Select .zip format.

• Click Other Options, set a password (e.g., 1234), then click Create.

![image](https://github.com/user-attachments/assets/cd932bdd-56b5-497c-9d06-4b32ef957367)

• A file named praveen.txt.zip will appear.

# Step 3: Open John the Ripper Terminal in Kali Linux
• Click on the Kali menu or press the Super (Windows) key.

• Search for “john” and click it — this opens the terminal with John the Ripper installed.

![image](https://github.com/user-attachments/assets/8dd83f55-1b16-4c95-b3fe-a6e83e6584e3)

• Or simply open a Terminal from the dock or desktop.

# Step 4: Navigate to the File Location
• In the terminal, switch to the Desktop where the ZIP file is located:

![image](https://github.com/user-attachments/assets/ddf20d00-42d0-4d35-afef-20321818d181)

# Step 5: Confirm the ZIP File is Present

• Run: “ls” command

![image](https://github.com/user-attachments/assets/24583c34-8f99-4f4b-82e3-82019ef1de3d)

• You should see praveen.txt.zip listed.

# Step 6: Generate Hash Using zip2john
• Execute:

![image](https://github.com/user-attachments/assets/d57a934f-eeec-48d8-b854-2218af6b5959)

# Step 7: Verify the Hash File (Optional)
• Open hash.txt to ensure it contains the hash line.

![image](https://github.com/user-attachments/assets/8544b492-c7a7-4831-9593-4fb7c46d1b8f)

Step 8: Start Cracking the Password
• Run:

![image](https://github.com/user-attachments/assets/a233ea30-c9ef-47c4-8373-8772c10ee979)


## OUTPUT:
Cracked Passwords from Hash File

![image](https://github.com/user-attachments/assets/13cdffa9-61de-4b9f-877d-6bfbdc4918f8)

• The terminal will display the filename and its cracked password.

## RESULT:
The password hashes were successfully cracked using John the Ripper.


