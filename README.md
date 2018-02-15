# mail-automation-gmail
E-mail automation using oauth 2.0.

In order to use this e-mail automation program you should :
1. Allow acces to less secure apps
2. Turn on Gmail API
3. Put the client_secret.json in the same diresctory as send_wa.py
3.1. Edit the sender variable in send_wa.py
4. Install the Google Client Library
5. Create a list of e-mail addresses in addresses.txt with each one on new line
6. Run in terminal with:
python send_wa.py
7. You could optionally set the time delay in seconds between sending the e-mails by changing the value of time.sleep(5) - currently set to five seconds.

For more info you could check:
https://stackoverflow.com/questions/37201250/sending-email-via-gmail-python


