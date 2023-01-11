<h1 align="center">Alien Crypter</h1>
<p align="center">

![image](https://user-images.githubusercontent.com/93733605/141330354-6cf4931e-64df-422a-90ed-43c8c5fc681b.png)


A crypter is a type of software that can encrypt, obfuscate, and manipulate malware, to make it harder to detect by security programs. It is used by cybercriminals to create malware that can bypass security programs by presenting itself as a harmless program until it gets installed. Types of crypters.

              
<h2 align="center">Disclaimer</h2>
<p>
Crypter is intended for educational and research purposes only. This software should not be used within any system or network for which you do not have permission, nor should it be used for any illegal or illicit purposes. The author takes no responsibility for any damages that may be caused by the software in this repository.
</p>
<p>
Once compiled, Crypter WILL encrypt the files on the computer on which it is executed. Whilst Crypter provides you with access to the decryption key, enabling you to decrypt any encrypted files, bugs and other issues could, in theory, interrupt or prevent a successful decryption. Consequently, a permanent and irreversible loss of data could occur. To avoid any potential damage, <b>you should only run Crypter on a test machine created for this purpose</b>.
</p>
<p>
Once again,<b>the author accepts no responsibility for any damages that may occur, and by downloading this software you accept and agree to this disclaimer.</b>
</p>

<h2 align="center">How Does it Work?</h2>

### Builder
The builder is the application that allows you to customise and build the Crypter Ransomware. Some of the options you can set include:

- Binary Executable File Icon
- GUI Title/Heading
- GUI Font and Background Colour
- Bitcoin Wallet Address
- Ransom Fee
- Ransom Message
- Payment Time Limit 
- File Shadow Copy Deletion
- Filetypes to Encrypt

and many more. After setting these options simply hit the <b>BUILD</b> button the build the executable.

### Ransomware
Once executed, Crypter will take the following steps:

- Generate an AES-256 bit encryption/decryption key and write it to key.txt in the current directory
- Search relevant locations (network drives, user directories, etc.) for matching files
- Encrypt all matching files
- Display the Crypter GUI to the victim
    


