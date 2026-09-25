Razvoj mobilnih aplikacij – Naloga 1: Hello World!

Ta repozitorij vsebuje rešitev prve naloge pri predmetu Razvoj mobilnih aplikacij. Glavni cilj naloge je bil spoznavanje z razvojnim okoljem Android Studio, strukturo Android projektov, delom z uporabniškim vmesnikom v XML ter osnovno programsko logiko v programskem jeziku Java.

Pregled aplikacije

Aplikacija prikazuje osnovni uporabniški vmesnik, zgrajen s postavitvijo ConstraintLayout, ter demonstrira uporabo osnovnih gradnikov in interakcij.

Ključne funkcionalnosti:

Uporabniški vmesnik (UI):

Uporaba dveh besedilnih polj (TextView) z nastavitvijo sloga (bold, 34sp) in večjezičnosti prek strings.xml.

Radio gumbi (RadioButton) za izbiro možnosti.

Potrditveno polje (CheckBox) za prijavo na novice / sprejem pogojev.

Glavni gumb za prijavo (Button).

Lebdeči akcijski gumb (FloatingActionButton) z ikono +.

Interaktivnost & Obvestila:

Toast: Ob kliku na gumb se izpiše sporočilo My first Android Studio application!.

Snackbar:

Privzeti prikaz obvestila Just another option for button ob kliku na FAB.

Prilagojena različica Snackbar, centrirana na sredino zaslona z izgledom (zaobljeni robovi, barve, pisava), ki posnema obvestilo tipa Toast.

Uporabljene tehnologije in orodja

Orodje: Android Studio

Programski jezik: Java

Predloga projekta: Empty Views Activity

Postavitev (Layout): ConstraintLayout

Viri (Resources): XML (postavitev, nizovni viri strings.xml)
  
Struktura projekta

Ključne datoteke v projektu:

app/
├── src/
│   └── main/
│       ├── java/.../MainActivity.java        # Glavna programska logika aktivnosti
│       ├── res/
│       │   ├── layout/activity_main.xml      # Postavitev uporabniškega vmesnika
│       │   └── values/strings.xml            # Besedilni viri (lokalizacija)
│       └── AndroidManifest.xml               # Konfiguracijska datoteka aplikacije


Namestitev in zagon

Klonirajte ta repozitorij:

git clone https://github.com/uporabnisko-ime/ime-repozitorija.git


Odprite Android Studio.

Izberite File > Open... in navigirajte do mape s prenesenim projektom.

Počakajte, da se zaključi sinhronizacija orodja Gradle.

Zaženite aplikacijo na Android emulatorju (AVD) ali povezani fizični napravi s pritiskom na zelen gumb Run (Shift + F10).

