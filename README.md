# SP2Cat
SP2Cat are an adapted version of the colabcat from someshkar that run [Hashcat](https://hashcat.net/) on [Google Colab](https://colab.research.google.com/), made specifically for the Student Project 2 - Cracking WiFi Passwords. Focusing on the -m 22000 (WPA-PBKDF2-PMKID+EAPOL) hash with the ability to resume sessions.


## Usage

* Upload the notbook SP2Cat.ipynb to colab, or click to the link below to open and make a copy.
* Make a folder called dothashcat in your google drive, this is where the <code>.restore</code>, <code>.log</code> and the <code>.potfile</code> will be stored.
* From there follows the steps in SP2Cat notebook 

## Similar projects
[someshkar/colabcat](https://github.com/someshkar/colabcat): Run Hashcat on Google Colab with session restore capabilities with Google Drive.
