# manjaro-awesome-iso
# 🧊 Awesome Manjaro Edition

**Custom Manjaro ISO with AwesomeWM, Nordic theme, and automated post-install setup**

---

## ⚙️ Overview / Áttekintés

This is a **custom Manjaro Linux ISO** featuring:

- Fully configured **AwesomeWM environment**
- Nordic GTK / Kvantum / LightDM theming
- Automatic **BTRFS snapshot management** with Snapper
- Preinstalled developer and system tools
- Automated **post-install script** for final configuration

Ez egy **egyedi Manjaro Linux ISO**, amely tartalmazza:

- Teljesen konfigurált **AwesomeWM környezetet**
- Nordic GTK / Kvantum / LightDM témát
- Automatikus **BTRFS snapshot kezelést** Snapper-rel
- Előtelepített fejlesztői és rendszereszközöket
- Automatikus **post-install szkriptet** a végső beállításokhoz

---

## 🪄 Installation Flow / Telepítési folyamat

1. **Boot the Live ISO / Indítsd el a Live ISO-t**  
   The system loads the **AwesomeWM live session** (default Manjaro theme).  
   A rendszer betölti az **AwesomeWM live sessiont** (alap Manjaro téma).

2. **Run the regular “Install Manjaro” / Futtasd a szokásos “Install Manjaro” folyamatot**  
   Once installed, reboot.  
   Telepítés után indítsd újra a rendszert.

3. **First login / Első belépés**  
   A terminal automatically opens showing a system configuration warning.  
   A terminál automatikusan megnyílik és megjeleníti a rendszerbeállítási figyelmeztetést.

4. **Run the post-install script / Futtasd a post-install szkriptet**  
   ```bash
   sudo bash awesome-install


The script will:

Configure Snapper & BTRFS maintenance timers

Install Nordic theme system-wide

Set up AwesomeWM Copycats configuration

Install packages, fonts, and developer tools

Clean up temporary files

Self-destruct after completion

A szkript elvégzi:

Snapper és BTRFS karbantartó időzítők beállítása

Nordic téma rendszer-szintű telepítése

AwesomeWM Copycats konfiguráció telepítése

Csomagok, betűtípusok és fejlesztői eszközök telepítése

Ideiglenes fájlok törlése

A szkript önmegsemmisítése a folyamat végén

Reboot / Újraindítás
Once finished, reboot to fully apply all changes.
A folyamat végén indítsd újra a gépet.

🖥️ Desktop Highlights / Főbb jellemzők

Window Manager / Ablakkezelő: AwesomeWM (Copycats configuration)

Theme / Téma: Nordic-standard-buttons

Icons / Ikonok: Nordzy-dark

Font / Betűtípus: FiraCode Nerd Font

Cursor / Kurzor: Nordic-cursors

System base / Rendszer alapja: Manjaro Stable 6.12 kernel

Filesystem / Fájlrendszer: BTRFS + Snapper automatic snapshots

Shell / Shell: Fish (for root / root felhasználónak)

🧩 Extra Feature — “Install XLibre” in Manjaro Hello

The Manjaro Hello screen is customized:

Bottom section includes ☕ Buy Me a Coffee

GitHub project link for updates

“Install XLibre” button launches the terminal installer automatically, adds the XLibre repo & GPG key, and replaces Xorg configuration.

A Manjaro Hello képernyő testreszabott:

Alján ☕ Buy Me a Coffee
 link

GitHub projekt link frissítésekhez

“Install XLibre” gomb elindítja a terminált, letölti a telepítő szkriptet, hozzáadja az XLibre repót és GPG kulcsot, majd lecseréli az Xorg konfigurációt

🔧 Requirements / Előfeltételek

Manjaro Linux (any edition with BTRFS recommended / BTRFS javasolt)

Stable internet connection / Stabil internetkapcsolat

Basic terminal knowledge / Alap terminálhasználati ismeret

📸 Screenshots / Képernyőképek (coming soon)
Live ISO	Installed System	Themed AwesomeWM
(preview1.png)	(preview2.png)	(preview3.png)


☕ Support / Támogatás

If you find this project useful, please support me:
Ha hasznosnak találod a projektet, támogasd:

👉[Buy me a coffee](https://buymeacoffee.com/rohambili)

🔗 ISO Download / ISO Letöltés

[⬇️ Latest XLibre ISO release](https://github.com/megvadulthangya/manjaro-awesome-iso/releases)

🧠 Credits / Készítette

Built on Manjaro Linux.
Inspired by Garuda Linux maintenance tools and Adi1090x rofi themes.
Custom integration & scripting by @megvadulthangya

Manjaro Linux alapokra építve.
Inspiráció: Garuda Linux karbantartó eszközei és Adi1090x rofi témák.
Egyedi integráció és szkriptek: @megvadulthangya
