KP NEXUS 2 – Android Studio Projekt

So erstellst du die APK:
1. ZIP entpacken.
2. Android Studio öffnen.
3. File > Open und den Ordner KP_NEXUS2_AndroidStudio auswählen.
4. Warten, bis Gradle Sync abgeschlossen ist (Internetverbindung erforderlich).
5. Build > Build Bundle(s) / APK(s) > Build APK(s).
6. Die APK liegt danach unter app/build/outputs/apk/debug/app-debug.apk.

Voraussetzungen:
- Android Studio
- JDK 17
- Android SDK Platform 35
- Gradle 8.9 (Android Gradle Plugin 8.7.3)
- Internetverbindung für Supabase und externe HTTPS-Bibliotheken

Die vorhandene HTML-App bleibt als Grundlage erhalten. Die MP3 wird lokal im APK mitgeliefert.
Die Musik startet erst beim Tippen auf „KP NEXUS STARTEN“ und wird beim Übergang zum Login ausgeblendet.
