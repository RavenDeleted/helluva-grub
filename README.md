😈 Helluva Boss GRUB Theme

<p align="center">
<img src="background.jpg" alt="Helluva Boss GRUB Background" width="100%">
</p>

<h2 align="center">🔥 WELCOME TO HELL 🔥</h2>

<p align="center">
A custom GRUB bootloader theme inspired by <b>Helluva Boss</b>.
</p>

<p align="center">
<img src="https://img.shields.io/badge/OS-Arch%20Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white">
<img src="https://img.shields.io/badge/Bootloader-GRUB-red?style=for-the-badge">
<img src="https://img.shields.io/badge/Resolution-1920x1080-purple?style=for-the-badge">
</p>

🎨 Features
🔥 Helluva Boss aesthetic
🩸 Dark red, black and purple color palette
😈 Custom background artwork
🖥️ 1920 × 1080 resolution
🐧 Designed for Arch Linux and GRUB
📁 Files
text
helluva-grub/
├── theme.txt
├── background.jpg
└── README.md

⚙️ Installation
Clone the repository:
bash
git clone https://github.com/RavenDeleted/helluva-grub.git

Copy the theme into GRUB's themes directory:
bash
sudo mkdir -p /boot/grub/themes/helluva-hazbin
sudo cp helluva-grub/theme.txt helluva-grub/background.jpg /boot/grub/themes/helluva-hazbin/

Configure GRUB to use the theme by setting GRUB_THEME in /etc/default/grub:
bash
GRUB_THEME="/boot/grub/themes/helluva-hazbin/theme.txt"

Regenerate the GRUB configuration:
bash
sudo grub-mkconfig -o /boot/grub/grub.cfg


Note: Back up your existing GRUB configuration before changing the active theme.

Credits

Inspired by:

Helluva Boss

Created by RavenDeleted.

📜 License

Artwork and characters belong to their respective copyright holders. This repository is an unofficial fan project and is not affiliated with or endorsed by the creators of either series.

<p align="center">
<b>SEE YOU IN HELL... 🔥</b>
</p>
