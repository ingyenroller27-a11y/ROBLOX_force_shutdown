🛡️ EduGuard: Digital Focus & Institutional Control System

EduGuard (kódnevén: SystemGuard) egy professzionális, Python-alapú végpontvédelmi megoldás, amelyet kifejezetten oktatási intézmények és tudatos szülők számára fejlesztettek ki. A szoftver célja a digitális fókusz fenntartása a nem kívánt szoftverek (például a Roblox) futtatásának teljes körű blokkolásával és automatizált eltávolításával.
🏫 Miért válassza az EduGuard-ot az iskolája számára?

Az informatika termekben a diákok figyelmének fenntartása kritikus feladat. A hagyományos szűrők gyakran kijátszhatók. Az EduGuard egy "zéró tolerancia" alapú megközelítést alkalmaz:

    Produktivitás növelése: Megszünteti a játékokkal kapcsolatos zavaró tényezőket az órák alatt.

    Adminisztratív kontroll: Megvédi az "Indítópult" (Startup) mappát az illetéktelen módosításoktól.

    Öngyógyító mechanizmus: A rendszer két párhuzamos folyamatból áll, amelyek védik és szükség esetén újraindítják egymást.

    Automatizált szankció: A többszöri sikertelen hozzáférési kísérlet után a rendszer automatikusan eltávolítja a tiltott szoftvert és leállítja a munkaállomást.

🚀 Kulcsfontosságú funkciók

    Páncélozott ablakkezelés: Az overrideredirect technológiának köszönhetően a blokkoló képernyő nem zárható be Alt+Tab, Alt+F4 vagy a tálca használatával.

    Registry-szintű védelem: A szoftver másodpercenként ellenőrzi és visszaállítja saját magát a Windows beállításjegyzékében (Registry), így a Feladatkezelőben történő letiltás hatástalan.

    Intelligens fókusz-menedzsment: A jelszókérő ablak agresszívan az előtérbe kényszeríti magát, ellehetetlenítve a háttérben futó egyéb alkalmazások elérését.

    Kereszt-figyelés (Watchdog): A Main.exe és Watch.exe folyamatosan monitorozza egymást. Ha az egyiket leállítják, a másik azonnal újraindítja azt.

    Türelmi idő és automatikus újranyitás: Helyes jelszó esetén a rendszer engedélyezi a szoftver futtatását, de a bezárás után a védelem azonnal újra aktívvá válik.

🛠️ Technikai specifikációk

A rendszer két fő komponensből áll:

    Main.exe: A központi figyelő és végrehajtó egység.

    Watch.exe: A háttérben futó őrszem, amely a perzisztenciát biztosítja.

Technológiák: Python 3.x, Tkinter, Psutil, PyGetWindow, WinReg.
📥 Telepítés (Rendszergazdák számára)

    Töltse le a legfrissebb .exe fájlokat a Releases menüpont alól.

    Futtassa a Deployer.exe-t rendszergazdaként a célgépen.

    A rendszer automatikusan telepíti magát az %APPDATA%\SystemGuard mappába és beállítja az automatikus indítást.

    Megjegyzés: Az alapértelmezett mesterjelszó: NoRobloxToday.

🔍 SEO & Kulcsszavak

Roblox blocker for schools, classroom management software, distraction-free learning, prevent games on school computers, parental control tool, Windows security automation, Python process monitor, educational firewall alternative.
📜 Licenc & Felelősségvállalás

Ez a szoftver oktatási célokra készült. A fejlesztő nem vállal felelősséget a nem megfelelő használatból eredő adatvesztésért (pl. automatikus leállás mentetlen munka esetén).
