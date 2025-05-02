# Detecting-steganography-with-tools-like-StegExpose-analyzing-file-signatures
### NAME : G LEKASRI
### REGISTER NUMBER : 212223100025
## AIM:
To detect hidden data using steganography detection tools like StegExpose and analyze file signatures for authenticity and manipulation.

## DESIGN STEPS:
### Step 1:
Install StegExpose or use the JAR version to detect steganography in image files.

### Step 2:
Run StegExpose on a directory of suspected image files using the command:

### Step 3:
Analyze file signatures using tools like file, binwalk, or xxd to check for inconsistencies or embedded content.

## PROCEDURE:
StegExpose and File Signature Analysis Commands

# Step 1: Download Image and Create Secret Message File
• Download a .jpeg image  from a trusted website or use own image.

![dfdi 1](https://github.com/user-attachments/assets/c05e8998-96be-4c58-a5c3-37d91bd78d65)


• Create a text file named secret with a confidential message:
![dfdi 2](https://github.com/user-attachments/assets/4b80adfd-2c87-42d2-94a1-cf23f1b0b238)


# Step 2: Install and Verify Steghide Tool
• To install Steghide on Kali linux,run:

• Confirm the installation by checking its version:

![dfdi 3](https://github.com/user-attachments/assets/aaad9de6-ff6b-4082-9b7a-482e570dcee3)

# Step 3: Embed the Secret Message into the Image
• Use the following command to embed secret into praveen.jpeg:

![dfdi 4](https://github.com/user-attachments/assets/c854dcb3-068d-4fcd-83d2-8b215b8595dc)

# Step 4: Delete the Original Secret File
• After embedding, delete the plaintext file:

![dfdi 5](https://github.com/user-attachments/assets/fc99fdb3-f2f7-4833-9d95-6c52f9c4b7dd)


## OUTPUT:
List of Images with Steganography Detection Scores and File Signature Details

# Step 1: Extract the Embedded Secret from the Image
![dfdi 6](https://github.com/user-attachments/assets/16f0e534-f472-4cb0-873c-cb353f52dbb7)

• To retrieve the hidden file:
• Enter the same passphrase used during embedding.
![dfdi 7](https://github.com/user-attachments/assets/5c966135-4ab8-499b-9270-eaa44295cb1c)

# Step 2: Verify the Extracted Message
• Display the extracted file content to verify:

• Ensure the message matches the original secret content.

• Another command to see the same secret message is

# Step 3: Retrieve Information About the Embedded Data
• To gather details about embedded content in the image:

![dfdi 8](https://github.com/user-attachments/assets/48a03c33-e2d4-4948-9a37-b5fbfb4a1f5e)

• This will display file type, size, and whether data is embedded.
## RESULT:
Hidden data was successfully detected and file signatures were analyzed for irregularities.
