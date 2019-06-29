# BaNX
Check if your NX Switch is banned or not.

# Why to use BaNX?

If you're already banned and you don't know it, it would be the same testing it, going online using your switch, or checking it using BaNX.

But if you really are not banned, and you want to know it, if you go online with your switch, your device will notify all your device activity log. That could become a ban. If you test it with BaNX, no information will be sent or reported.

## Changelog

Release 0.1 - Updated to 8.1.0

### Warning

If running BaNX you get you're not banned, do not repeat the procedure continuosly or you will be banned. Do it just for once per day if you need it.

Disclaimer: Using your cert out of your switch could become your switch banned. Use at your own risk.

### Instructions

This app will be run from Windows. But you will need your switch cert to know if it is ban or not.

Running latest releases of atmosphere in your switch will automatically create a copy of your prodinfo file which contains inside your switch certificate.

1.- So run atmosphere.

2.- Power off your switch.

3.- Extract your microSD from your switch and plugin into your PC.

4.- Browse to sd:/atmosphere/automatic_backups

5.- There you will find a file like: YOUR_SWITCH_SERIAL_NUMBER_PRODINFO.bin

6.- Download the [latest release](https://github.com/RetroGamer74/BaNX/releases) of BaNX from this repository.

7.- Copy the prodinfo file stored in your sd:/atmosphere/automatic_backups into the BaNX/ExtractYourCert folder

8.- Go to RetroGamer Discord (see CREDITS), to the channel #switch and get the keys.cfg file.

9.- Copy it into BaNX/ExtractYourCert folder.

10.- Run RunThis_ExtractYourCert.cmd file.

11.- A new nx_tls_client_cert.pfx file will be created.

12.- Copy nx_tls_client_cert.pfx into BaNX folder.

10.- Go to BaNX folder and run BaNX.

11.- Press Check button and cross your fingers.


That's all.

## Credits
Here is an invitation to RetroGamer discord: [https://t.co/WZGZquHe87](https://t.co/WZGZquHe87)

Certificate Extractor is an EXE conversion from python files from other projects like CertNXExtractionPack

BaNX by RetroGamer_74
