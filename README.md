## ⚠️ Disclaimer: Important Notice Regarding Usage ⚠️

**Please be advised that Google Colab has recently updated its terms of service, which may impact the usage of this repository. Users are strongly advised NOT to use the tools or code provided in this repository (SP2Cat) for their projects, as it may result in the suspension or banning of your Google account on Colab.**

## SP2Cat

[![image](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/teddy-flow/SP2Cat/blob/master/SP2Cat.ipynb)

SP2Cat is an adapted version of `someshkar/colabcat` that runs Hashcat on Google Colab, specifically created for the Student Project 2: Operation Bloodhound - Cracking WiFi Passwords. It focuses on the `-m 22000 (WPA-PBKDF2-PMKID+EAPOL)` hash with the ability to resume sessions.

### Usage

1. Upload the notebook SP2Cat.ipynb to Colab, or click the link below to open and make a copy.
2. Make a folder called `dothashcat` and a subfolder called `hashes` (copy the hashfile here) in your Google Drive, where the `.restore`, `.log`, and the `.potfile` will be stored.
3. Follow the steps in the SP2Cat notebook.

### Similar Projects
- [someshkar/colabcat](https://github.com/someshkar/colabcat): Run Hashcat on Google Colab with session restore capabilities with Google Drive.

