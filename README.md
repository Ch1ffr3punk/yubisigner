# yubisigner

Hardware-based, multi-standard file signing with YubiKey  
yubisign is a compact GUI program for signing and verifying  
files with YubiKey. It supports international cryptographic  
standards and offers maximum security through hardware keys.  

## Features

YubiKey hardware security  

- 4 hash algorithms: RIPEMD-256, SHA-256, SM3 and Streebog-256  
- RFC-compliant signatures with CRLF  
- Compact GUI with dark/light mode  
- Identicon for author verification (see [yubicrypt](https://github.com/Ch1ffr3punk/yubicrypt))  
- UTF-8 support for international characters in author string  
  of detached .sig file

## Example Signature file (.sig)
```
Author: Ch1ffr3punk  
Signed at: 2026-03-09 05:59:14 +0000  
Filename: yubisigner-windows-amd64.exe  
File size: 25772544 bytes  
Email: ch1ffr3punk@gmail.com  
URL: https://oc2mx.net  
  RIPEMD-256: 1222d3136827f139a4e7673e171b63fb6de20e2c48d44a257302cd5b70f84c91  
     SHA-256: 07475119d6fc9d85527141267eab6c981dd365993d575b99796f481033951371  
         SM3: dcca6112ce3096ea72565efee5a454e64cd4ae4be015162630a0aa21ec9e305f  
Streebog-256: 60e69090e25875bd063def008cb4287e848f4908219479e1c76dc46f0844ca4d  
-----BEGIN YUBISIGNER ED25519 SIGNATURE-----  
8a5f8adfec9690b8ae6ca95dc23811463fcce5bbba0d841f49b7d3f7a89ad149  
04f33554f89d956fce08b6beb7249d67ca87fa495ce4c5c3a0d094842242c78a  
4f36a1dff914ae261f470eeafc02469e44a527acc5bddc60e7c163ab357a4206  
-----END YUBISIGNER ED25519 SIGNATURE-----  
```
![yubisigner](img/1.png)

![yubisigner](img/2.png)  

If you like yubisigner, as much as I do,  consider a small          
donation in crypto currencies or buy me a coffee.           
```  
BTC: bc1qkluy2kj8ay64jjsk0wrfynp8gvjwet9926rdel       
Nym: n1f0r6zzu5hgh4rprk2v2gqcyr0f5fr84zv69d3x       
XMR: 45TJx8ZHngM4GuNfYxRw7R7vRyFgfMVp862JqycMrPmyfTfJAYcQGEzT27wL1z5RG1b5XfRPJk97KeZr1svK8qES2z1uZrS        
```
<a href="https://www.buymeacoffee.com/Ch1ffr3punk" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-yellow.png" alt="Buy Me A Coffee" height="41" width="174"></a>

yubisigner is dedicated to Alice and Bob.  

