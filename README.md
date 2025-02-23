Message Encryption and Decryption Based on Image:
This project basically illustrates a very simple way of encrypting and decrypting a secret message through an image using Python and OpenCV. 

Requirements:
Python 3.x
OpenCV
OS module
or use vs code for run the code...

Installation,
Install OpenCV

pip install opencv-python
Now clone this repository and change the repository to the project directory:


Usage:
Encrypting a Message
Place an image file (.jpg or any of your desired image) within the project directory.

Run the script:
python project.py
Enter the secret message and the passcode when asked. 
An encrypted image (encryptedImage.jpg) is created and opened.

Decrypting a message:
Again Run the script
python project.py
Enter the passcode for decryption. 
If the passcode is correct, we will display the decrypted message. 

Code Explanation:
d and c dictionaries are used for direct character conversion to their ASCII values and vice versa.
The encoded message is there by changing the pixel values of the image based on ASCII values of the characters in the secret message.
The passcode guarantees that only authorized users can decrypt this message.
