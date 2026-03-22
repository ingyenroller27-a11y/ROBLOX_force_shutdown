# 🛡️ ROBLOX_force_shutdown v3.0 (Omni-Shield)

**A végső megoldás a digitális fókusz fenntartására.** A `ROBLOX_force_shutdown` egy agresszív folyamatkezelő és rendszertisztító szoftver, amelyet arra terveztek, hogy felszámolja a nem kívánt játékidőt oktatási intézményekben és otthoni környezetben.

### 🚀 Miért a v3.0-át válaszd?
A rendszer **"zéró tolerancia"** elven működik. Ha tiltott szoftvert észlel, a felhasználónak 30 másodperce van a jelszó megadására, különben a szoftver törli a játékot és leállítja a számítógépet.

### 🔑 Egyedi jelszó beállítása (Customization)
A szoftver alapértelmezett mesterjelszava: `NoRobloxToday`.
Biztonsági okokból javasolt ennek megváltoztatása a fordítás előtt:
1. Nyisd meg a `Main.py` fájlt egy szövegszerkesztővel.
2. Keresd meg az `ADMIN_PASS = "NoRobloxToday"` sort a fájl elején.
3. Írd át a jelszót a sajátodra (pl. `ADMIN_PASS = "TitkosJelszo123"`).
4. Fordítsd újra a projektet a `PyInstaller` segítségével.

### 🛠️ Telepítés (Pár kattintással)
1. Töltsd le a `Main.exe`, `Watch.exe` és `Deployer.exe` fájlokat.
2. Indítsd el a **Deployer.exe**-t.
3. Válaszd ki a két másik fájlt a tallózóval.
4. Kattints a **TELEPÍTÉS** gombra.
5. A rendszer automatikusan bemásolja magát az `%APPDATA%` mappába, beállítja az automatikus indítást, és aktiválja az őrszemet.

### 💎 Kulcsfunkciók
* **Anti-Bypass GUI:** Blokkolja az Alt+Tab, Alt+F4 és a tálca használatát.
* **Brute-Force Cleanup:** Sikertelen feloldáskor megsemmisíti a `%LOCALAPPDATA%\Roblox` mappát.
* **Deceptive UX:** A törlés alatt gyanúmentes *"Windows Rendszerfrissítés"* üzenetet mutat.
* **Dual-Process Watchdog:** A `Main.exe` és `Watch.exe` folyamatosan újraindítják egymást, ha az egyik leállna.

**Mesterjelszó:** `NoRobloxToday`
