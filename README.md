# Linux-CAA-Install-Guide-VITAP

This is brief installation guide to anyone who's having difficulties setting up the Sophos Client Authentication Agent on Linux for the VIT-AP campus

**Note:** _Make sure you're logged in to the VIT-AP Hostel Network before beginning the installation_

## The ReadMe File

Start with downloading the Linux 64/32 client from [here](https://hfw.vitap.ac.in:445/)

![sophos-download-page](./assets/sophos-page.png)

```
Unpack all files into your HOME directory (tar -xzvfp <FILENAME>).
You should have the following files:
<HOME>/.caa/
            ca-cert.pem
            caa.conf
            README
       bin/
            caa
```

The above step can be done either via the Terminal or with the GUI

### via Terminal

(Right-click and select extract after moving the .tar.gz file to the )
