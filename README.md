
# 🏔️ Awesome Manjaro Edition

**My personal, unified system installer - Create the same consistent AwesomeWM environment across all my devices**

---

## ⚙️ Overview / Áttekintés

This project is my **personal, unified system installer**. I created it to easily replicate my preferred computing environment—with my core workflow tools and consistent theming—across different machines.

At its core, this is a **minimal custom Manjaro Linux ISO** featuring:

- Fully configured **AwesomeWM environment** using Nordic color palette
- Nordic GTK / Kvantum / LightDM theming  
- Automatic **BTRFS snapshot management** with Snapper
- Essential developer and system tools
- Automated **post-install script** for final configuration

Ez a projekt **személyes, egységes rendszertelepítőm**. Azért készítettem, hogy könnyedén reprodukálni tudjam az általam preferált számítógépes környezetet—alapvető munkafolyamat-eszközeimmel és egységes témázásával—bármelyik eszközömre.

A projekt magja egy **minimális Manjaro Linux ISO**, amely tartalmazza:

- Teljesen konfigurált **AwesomeWM környezetet** Nordic színpalettával
- Nordic GTK / Kvantum / LightDM témát
- Automatikus **BTRFS snapshot kezelést** Snapper-rel
- Alapvető fejlesztői és rendszereszközöket
- Automatikus **post-install szkriptet** a végső beállításokhoz

---

## 🖥️ Desktop Highlights / Főbb jellemzők

- **Window Manager / Ablakkezelő:** AwesomeWM (Copycats configuration with Nordic colors)
- **Theme / Téma:** Nordic-standard-buttons
- **Icons / Ikonok:** Nordzy-dark
- **Font / Betűtípus:** FiraCode Nerd Font
- **Cursor / Kurzor:** Nordic-cursors
- **Color Scheme / Színpaletta:** Complete Nordic color harmony across all components
- **System base / Rendszer alapja:** Manjaro Stable 6.12 kernel
- **Filesystem / Fájlrendszer:** BTRFS + Snapper automatic snapshots
- **Shell / Shell:** Fish (for root / root felhasználónak)

---

## 🪄 Installation Flow / Telepítési folyamat

### 1. **Boot the Live ISO / Indítsd el a Live ISO-t**
The system loads the **AwesomeWM live session** (default Manjaro theme).  
A rendszer betölti az **AwesomeWM live sessiont** (alap Manjaro téma).

### 2. **Run the regular "Install Manjaro" / Futtasd a szokásos "Install Manjaro" folyamatot**
Once installed, reboot.  
Telepítés után indítsd újra a rendszert.

### 3. **First login / Első belépés**
A terminal automatically opens showing a system configuration warning.  
A terminál automatikusan megnyílik és megjeleníti a rendszerbeállítási figyelmeztetést.

### 4. **Run the post-install script / Futtasd a post-install szkriptet**
```bash
sudo bash awesome-install
```

**🔍 Want to see what happens? / Szeretnéd látni, hogy mi történik?**  
You can review the installation script before running: [View awesome-install source](https://github.com/megvadulthangya/iso-profiles/blob/awesome-nord/community/awesome/desktop-overlay/opt/system_setup/awesome-install)  
A telepítő szkriptet megtekintheted futtatás előtt: [awesome-install forráskódja](https://github.com/megvadulthangya/iso-profiles/blob/awesome-nord/community/awesome/desktop-overlay/opt/system_setup/awesome-install)

**The script will set up my core environment:**
- Configure Snapper & BTRFS maintenance timers
- Install complete Nordic theme system-wide
- Set up AwesomeWM Copycats configuration with Nordic color scheme
- Install essential packages, fonts, and developer tools
- Clean up temporary files
- Self-destruct after completion

**A szkript feltelepíti az alapvető környezetemet:**
- Snapper és BTRFS karbantartó időzítők beállítása
- Teljes Nordic téma rendszer-szintű telepítése
- AwesomeWM Copycats konfiguráció beállítása Nordic színpalettával
- Alapvető csomagok, betűtípusok és fejlesztői eszközök telepítése
- Ideiglenes fájlok törlése
- A szkript önmegsemmisítése a folyamat végén

### 5. **Reboot / Újraindítás**
Once finished, reboot to fully apply all changes and get my consistent environment.  
A folyamat végén indítsd újra a gépet, hogy a teljes környezet aktiválódjon.

---

## 🧩 Extra Feature — "Install XLibre" in Manjaro Hello

> **Note:** This feature is only available in the installed system, not in the Live ISO.

The Manjaro Hello screen is customized in the installed system:

- Bottom section includes ☕ Buy Me a Coffee
- GitHub project link for updates
- "Install XLibre" button launches the terminal installer automatically, adds the XLibre repo & GPG key, and replaces Xorg configuration.

> **Megjegyzés:** Ez a funkció csak a telepített rendszerben érhető el, nem a Live ISO-ban.

A Manjaro Hello képernyő a telepített rendszerben testreszabott:

- Alján ☕ Buy Me a Coffee link
- GitHub projekt link frissítésekhez
- "Install XLibre" gomb elindítja a terminált, letölti a telepítő szkriptet, hozzáadja az XLibre repót és GPG kulcsot, majd lecseréli az Xorg konfigurációt

---

## 🔧 Requirements / Előfeltételek

- USE BTRFS recommended / BTRFS javasolt
- Stable internet connection / Stabil internetkapcsolat
- Basic terminal knowledge / Alap terminálhasználati ismeret

---

## 📸 Screenshots / Képernyőképek (coming soon)

| Live ISO | Installed System | Themed AwesomeWM |
|----------|------------------|------------------|
| (preview1.png) | (preview2.png) | (preview3.png) |

---

## ☕ Support / Támogatás

If you find this project useful, please support me:  
Ha hasznosnak találod a projektet, támogasd:

👉 [Buy me a coffee](https://buymeacoffee.com/rohambili)

---

## 🔗 ISO Download / ISO Letöltés

[⬇️ Latest Awesome manjaro ISO release](https://github.com/megvadulthangya/manjaro-awesome-iso/releases)

---

## 🧠 Credits / Készítette

**Built upon / Alapjául szolgált:**
- 🐧 [Manjaro Linux](https://manjaro.org/)
- 🎨 [Nordic Theme](https://github.com/EliverLara/Nordic)
- ⚡ [AwesomeWM Copycats](https://github.com/lcpz/awesome-copycats)

**Inspiration / Inspiráció:**
- 🛠️ [Garuda Linux Tools](https://gitlab.com/garuda-linux/tools)
- 🎭 [Adi1090x Rofi Themes](https://github.com/adi1090x/rofi)

**Installation Script / Telepítő szkript:**
- 📜 [awesome-install source](https://github.com/megvadulthangya/iso-profiles/blob/awesome-nord/community/awesome/desktop-overlay/opt/system_setup/awesome-install)

**Custom integration & scripting / Egyedi integráció:**
- 👨💻 [@megvadulthangya](https://github.com/megvadulthangya)
```

