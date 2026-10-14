NEON DASH — aplikacja Android (offline)

Projekt Android Studio z grą NEON DASH działającą w pełnoekranowym WebView.
Nie jest to gotowy plik APK. Aby otrzymać APK:
1. Zainstaluj Android Studio z Android SDK 35 i JDK 17.
2. W Android Studio wybierz File > Open i wskaż folder NEON_DASH_Android.
3. Poczekaj na synchronizację Gradle i instalację wymaganych składników.
4. Wybierz Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Plik znajdziesz w app/build/outputs/apk/debug/app-debug.apk.
6. Przenieś APK na telefon i zainstaluj, pozwalając na instalację z tego źródła.

Gra działa bez internetu; asset app/src/main/assets/index.html zawiera całą grę.
Muzyka uruchamia się po dotknięciu przycisku GRAJ.
Rekordy i monety zostają zapisane w danych aplikacji Android; dane z Chrome nie przenoszą się automatycznie.

Uwaga: nie dołączamy skompilowanego APK, bo środowisko tworzenia nie ma Android SDK.
