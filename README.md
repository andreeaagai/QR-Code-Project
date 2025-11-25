# QR-Code-Project

![Node.js](https://img.shields.io/badge/Node.js-18-green?style=for-the-badge)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

## Descriere
QR-Code-Project este un tool de linie de comandă creat cu Node.js care generează coduri QR dintr-un URL introdus de utilizator și salvează URL-ul într-un fișier text. Proiectul este simplu, dar util pentru generarea rapidă de coduri QR fără interfață web.

---

## Funcționalități principale
- Prompt interactiv pentru introducerea URL-ului folosind **Inquirer**  
- Generare cod QR din URL folosind **qr-image**  
- Salvare cod QR ca imagine PNG (`qr_img.png`)  
- Salvare URL introdus într-un fișier text (`URL.txt`)  
- Mesaje informative pentru confirmarea salvării fișierelor

---

## Tech Stack
- **Node.js** – runtime pentru JavaScript  
- **Inquirer** – pentru input interactiv în terminal  
- **qr-image** – pentru generarea codurilor QR  
- **fs (File System)** – pentru salvarea fișierelor local

---
## Screenshots / Demo GIF
![QR Code](./qr_img.png)
---

## Instalare & Setup
1. Clonează repository-ul:

```bash
git clone https://github.com/andreeaagai/QR-Code-Project.git
