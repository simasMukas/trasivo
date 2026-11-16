# Trasivo

## Lietuviškai

[Svetainė](https://simasmukas.github.io/trasivo/) · [GitHub](https://github.com/simasMukas/trasivo)

**Trasivo** – mobiliesiems pritaikytas maršruto vaizdo įrašų kūrimo įrankis. Įkelk vienos GPS veiklos GPX, FIT arba TCX failą ir sugeneruok filmuką. Sąsaja ir rodmenys palaiko LT / EN.

### Naudojimas

1. Atidaryk paskelbtą svetainę naršyklėje.
2. Paspausk **Pasirinkti failą**. Jei failo neturi, atidaryk **Kur gauti failą?**.
3. Įkelk GPX, FIT arba TCX su GPS koordinatėmis.
4. Paspausk **Generuoti filmuką**, palik ekraną įjungtą ir sulauk atsisiuntimo mygtuko.
5. Papildomi pasirinkimai atidaromi per **Nustatymai**.

ZIP su viena treniruote gali įkelti tiesiogiai (iki 32 MB, išskleistas failas iki 64 MB). Apple Health XML, CSV ir JSON nepalaikomi. Strava treniruotės nuoroda naudojama tik atsisiuntimui atidaryti, ne tiesioginiam importui. Originalus veiklos FIT paprastai išsaugo daugiau rodmenų; navigacijos GPX gali neturėti laiko ar pulso.

### Failas iš Strava

Pasirink **Įkelti iš Strava**, įklijuok pilną savo treniruotės nuorodą ir spausk **Atsisiųsti TCX iš Strava**. Atsisiuntimas vyksta Strava svetainėje; ten gali reikėti prisijungti. Grįžk ir pasirink atsisiųstą failą. API rakto ar Trasivo paskyros nereikia. Sutrumpintą bendrinimo nuorodą pirmiausia atidaryk naršyklėje ir nukopijuok pilną adresą. Telefone gali reikėti kompiuterinės svetainės versijos.

### GitHub Pages

Tai statinė svetainė; diegti priklausomybių ar kurti serverio nereikia.

Repository → **Settings → Pages → Deploy from a branch → main → /(root) → Save**.

Pradinis failas – `index.html`. Po publikavimo puslapis atidaromas telefonu per viešą HTTPS nuorodą.

### Privatumas ir veikimo ribos

Veiklos failas skaitomas ir vaizdas generuojamas naudotojo naršyklėje. Programėlė neturi įkėlimo serverio ar paskyrų. Žemėlapio vaizdai, šriftai ir bibliotekos gaunami iš išorinių paslaugų, todėl reikia interneto. Pasirinkta kalba įsimenama tame įrenginyje.

Generuojant puslapis turi likti atidarytas. Priklausomai nuo naršyklės, failas generuojamas kaip MP4 arba WebM. Tikras veikimas skirtinguose telefonuose gali skirtis.

Instrukcijos eksportui – pačioje programėlėje ir [EXPORT_GUIDE.md](EXPORT_GUIDE.md).

Pradinio puslapio ženklas ir išorinės paslaugos aprašytos [NOTICE.md](NOTICE.md).

---

## English

[Website](https://simasmukas.github.io/trasivo/) · [GitHub](https://github.com/simasMukas/trasivo)

**Trasivo** is a mobile-first GPS route video maker. Upload a GPX, FIT or TCX file from one GPS-recorded activity and generate a video. The interface and on-video stats support Lithuanian and English.

### Usage

1. Open the published website in your browser.
2. Select **Choose a file**. If you need an activity file, open **Where do I get a file?**.
3. Upload a GPX, FIT or TCX file containing GPS coordinates.
4. Select **Generate video**, keep your screen on and wait for the download button.
5. Optional controls are available under **Settings**.

Upload ZIP archives containing one activity directly (up to 32 MB compressed, 64 MB extracted). Apple Health XML, CSV and JSON are not supported. A Strava activity link opens the download; it does not directly import the activity. An original activity FIT usually preserves more stats; a navigation-only GPX may contain no timestamps or heart-rate data.

### File from Strava

Select **Upload from Strava**, paste the full URL of your own activity and select **Download TCX from Strava**. The download happens on Strava and may require signing in there. Return and choose the downloaded file. No API key or Trasivo account is needed. Open shortened share links in your browser to obtain the full activity URL. Phone users may need the desktop website.

### GitHub Pages

This is a static website; no dependency installation, build step or backend is needed.

Repository → **Settings → Pages → Deploy from a branch → main → /(root) → Save**.

The entry file is `index.html`. After deployment, the public HTTPS URL can be opened directly on a phone.

### Privacy and limitations

Activity files are read and videos are generated in the user’s browser. The app has no upload server or user accounts. Map imagery, fonts and libraries are fetched from third-party services, so an internet connection is required. The selected language is remembered on that device.

Keep the page open during video generation. Depending on the browser, the output is MP4 or WebM. Actual behaviour can vary across phones.

File-export instructions are available in the app and in [EXPORT_GUIDE.md](EXPORT_GUIDE.md).

The homepage identity and external resources are described in [NOTICE.md](NOTICE.md).
