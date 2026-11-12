🔥 WELCOME TO HELL — Helluva Boss GRUB Theme

<p align="center">
<strong>A little taste of Hell every time you boot your machine.</strong>
</p>

<p align="center">
A custom GRUB bootloader theme inspired by the chaotic, dark and flamboyant universe of <strong>Helluva Boss</strong>.
</p>

😈 Overview

WELCOME TO HELL is a custom GRUB theme designed to bring a touch of infernal style to your Linux boot experience.

Featuring a dark aesthetic, demonic atmosphere and a distinctive red, black and purple color palette, this theme transforms your ordinary bootloader into something straight out of the underworld.

Because even your bootloader deserves a little chaos.

🔥 Features
🩸 Helluva Boss-inspired aesthetic — A dark and distinctive visual identity.
🔥 Infernal color palette — Deep reds, blacks and purples.
😈 Custom artwork — Unique background inspired by the series.
🖥️ Full HD resolution — Designed for 1920 × 1080 displays.
🐧 Linux compatible — Designed for GRUB-based Linux distributions.
🎨 Custom GRUB interface — A more personalized boot experience.
🖼️ Preview

<p align="center">
<img src="background.jpg" alt="WELCOME TO HELL - GRUB Background" width="85%">
</p>

📁 Project Structure
text
helluva-grub/
├── theme.txt
├── background.jpg
└── README.md

File	Description
theme.txt	GRUB theme configuration
background.jpg	Custom GRUB background artwork
README.md	Project documentation
⚙️ Installation
1. Clone the repository
bash
git clone https://github.com/RavenDeleted/helluva-grub.git
cd helluva-grub

2. Create the theme directory
bash
sudo mkdir -p /boot/grub/themes/helluva-hazbin

3. Copy the theme files
bash
sudo cp theme.txt background.jpg /boot/grub/themes/helluva-hazbin/

4. Configure GRUB

Open the GRUB configuration file:

bash
sudo nano /etc/default/grub


Add or update the following line:

bash
GRUB_THEME="/boot/grub/themes/helluva-hazbin/theme.txt"


Make sure there is only one active GRUB_THEME entry.

5. Regenerate GRUB configuration

For Arch Linux and other distributions using grub-mkconfig:

bash
sudo grub-mkconfig -o /boot/grub/grub.cfg

6. Reboot
bash
sudo reboot


If everything is configured correctly, your next boot will take you straight to Hell. 🔥

Important: Back up your existing GRUB configuration before making changes. GRUB installation paths may differ depending on your distribution and boot setup. Make sure the theme files are accessible from your boot partition.
🐧 Compatibility
Component	Support
Bootloader	GRUB
Operating systems	Linux
Main target	Arch Linux
Display resolution	1920 × 1080
Theme format	GRUB Theme

Other GRUB-based distributions may also work, but have not necessarily been tested.

🛠️ Troubleshooting

Theme does not appear after reboot?

Check that GRUB_THEME points to the correct theme.txt file.
Make sure both theme files are present in the theme directory.
Regenerate the GRUB configuration.
Verify that GRUB can access the theme files.

Background does not display correctly?

Check that background.jpg is in the same directory as theme.txt.
Verify that the image path inside theme.txt is correct.
Keep in mind that the theme was designed for 1920 × 1080 displays.
🎭 Credits
Inspired by: Helluva Boss
Theme creator: RavenDeleted
Artwork: Custom background artwork included in this repository.
📜 License & Disclaimer

This repository is an unofficial fan-made project created for personal customization and entertainment purposes.

Helluva Boss, its characters, artwork and associated intellectual property belong to their respective copyright holders.

This project is not affiliated with, endorsed by, or officially connected to the creators, production studios or rights holders of Helluva Boss.

Please respect the original creators and their intellectual property.

<p align="center">
<strong>🔥 WELCOME TO HELL 🔥</strong>
<br>
<em>Where every boot is a descent into chaos.</em>
<br><br>
Made with 🩸 by <a href="https://github.com/RavenDeleted">RavenDeleted</a>
</p>

<p align="center">
<strong>SEE YOU IN HELL...</strong> 😈
</p>
