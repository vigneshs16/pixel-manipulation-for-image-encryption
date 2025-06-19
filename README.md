Basic Image Encryption Tool
A simple educational image encryption tool built with pure Python — no external libraries required.
It supports basic encryption techniques on PPM image format for learning and experimenting with image manipulation and encryption.

🎯 Purpose
This tool is designed to help students and self-learners understand basic image encryption concepts through:

Simple XOR-based encryption

Mathematical operations on pixel data

Pixel swapping techniques

RGB channel shifting

⚠️ Important Ethical Notice
This tool is for educational use only.

Do not use it to encrypt or tamper with images you do not own or have permission to modify.

The author is not responsible for any misuse.

✨ Features
🚀 Core Functionality
Create sample PPM images

Encrypt PPM images using different methods

Decrypt previously encrypted PPM images

View supported encryption methods

Simple console-based menu for easy use

🔐 Supported Encryption Methods
XOR Encryption — password-based

Mathematical Operations — add/subtract pixels

Pixel Swapping — swap pixels based on password

Channel Shifting — shift RGB channels

🛠️ Technical Details
Language: Python (3.x)

Libraries: Only built-in libraries (os, random, hashlib)

Image format: PPM (Portable PixMap, P3 format — plain text)

🚀 Getting Started
Prerequisites
Python 3.x installed

Terminal or Command Prompt

Running the Tool
bash
Copy
Edit
python basic_image_encryption.py
Main Menu
mathematica
Copy
Edit
1. Create Sample Image
2. Encrypt Image
3. Decrypt Image
4. View Methods
5. Exit
Creating a Sample Image
Choose option 1.

Provide a filename (e.g., sample.ppm).

Enter width and height (default 100x100).

Encrypting an Image
Choose option 2.

Enter image filename (.ppm format).

Select encryption method.

Provide required parameters (password/key/shift).

Save encrypted image.

Decrypting an Image
Choose option 3.

Provide encrypted image filename.

Select correct method and parameters.

Save decrypted image.

View Methods
Choose option 4 to see supported encryption methods.

📖 Educational Value
Learning Objectives
Understand pixel-based image formats

Learn about basic encryption techniques

Experiment with RGB manipulation

See effects of different encryption methods on images

Use Cases
Computer science education

Cryptography learning

Image processing experiments

Python programming practice

🔧 Customization
You can easily customize or extend this tool:

Modify or add new encryption methods

Support new image formats (e.g., PNG, JPEG using external libraries)

Create batch encryption scripts

📋 Limitations
Only works with P3 PPM images (plain text format)

No compression or advanced encryption — for learning only

Not suitable for production use

🤝 Contributing
Contributions are welcome:

Bug fixes

New encryption methods

Code optimizations

Better user interface (e.g., GUI)

📄 License
This project is released under the MIT License.

⚖️ Legal Disclaimer
Use responsibly. The author is not liable for any misuse.

