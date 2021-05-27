# What is it?

<!---->
ILOVEYOU, sometimes referred to as Love Bug or Love Letter, was a computer worm that attacked tens of millions of Windows personal computers on and after 5 May 2000 local time in the Philippines when it started spreading as an email message with the subject line "ILOVEYOU" and the attachment "LOVE-LETTER-FOR-YOU.txt.vbs".

— Wikipedia, ILOVEYOU

This is a formatted version of the ILOVEYOU worm also known as Love Letter. It includes comments which explains the routines that are used by the worm to infect and spread itself.
<!---->

# How it works 

The worm is distributed primarily through email, most prominently Microsoft Outlook at the time. It does so by sending an email to each of the victim's contacts, listed in their Address Book.

When executed, it infects different files in the system by writing itself to document files, MP3s/MP2s, JPEG, and other Visual Basic scripts and changing their extension to .vbs, making them executable.

It also makes it so, after having executed the script the first time, will execute on each startup of the computer, making it very difficult to stop.

It relies on the fact that Windows will automatically execute any Visual Basic Script files, when opened from the file explorer or from Outlook, making it trivial for a victim to accidentally execute it.

# Warning / Disclaimer

This program and its source files are only uploaded for educational purposes. Do not execute this program if you do not know what it does and what the risks are. I highly recommend you do not execute this file on your personal machine. This script should only be executed in a VM.

# Credits

This code was obtained by https://Cexx.org/


