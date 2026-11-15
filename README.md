# Trasivo

## Lietuviškai

**Trasivo** – mobiliesiems pritaikytas maršruto vaizdo įrašų kūrimo įrankis. Įkelk vienos GPS veiklos GPX, FIT arba TCX failą ir sugeneruok filmuką. Sąsaja ir rodmenys palaiko LT / EN.

### Naudojimas

1. Atidaryk paskelbtą svetainę naršyklėje.
2. Paspausk **Pasirinkti failą**. Jei failo neturi, atidaryk **Kur gauti failą?**.
3. Įkelk GPX, FIT arba TCX su GPS koordinatėmis.
4. Paspausk **Generuoti filmuką**, palik ekraną įjungtą ir sulauk atsisiuntimo mygtuko.
5. Papildomi pasirinkimai atidaromi per **Nustatymai**.

ZIP archyvą prieš įkėlimą išskleisk. Apple Health XML, CSV, JSON ir bendrinimo nuorodos nepalaikomos. Originalus veiklos FIT paprastai išsaugo daugiau rodmenų; navigacijos GPX gali neturėti laiko ar pulso.

### GitHub Pages

Tai statinė svetainė; diegti priklausomybių ar kurti serverio nereikia.

Repository → **Settings → Pages → Deploy from a branch → main → /(root) → Save**.

Pradinis failas – `index.html`. Po publikavimo puslapis atidaromas telefonu per viešą HTTPS nuorodą.

### Privatumas ir veikimo ribos

Veiklos failas skaitomas ir vaizdas generuojamas naudotojo naršyklėje. Programėlė neturi įkėlimo serverio ar paskyrų. Žemėlapio vaizdai, šriftai ir bibliotekos gaunami iš išorinių paslaugų, todėl reikia interneto. Pasirinkta kalba įsimenama tame įrenginyje.

Generuojant puslapis turi likti atidarytas. Priklausomai nuo naršyklės, failas generuojamas kaip MP4 arba WebM. Tikras veikimas skirtinguose telefonuose gali skirtis.

Instrukcijos eksportui – pačioje programėlėje ir [EXPORT_GUIDE.md](EXPORT_GUIDE.md).

Pradinio puslapio nuotraukos autorystė ir išorinės paslaugos nurodytos [NOTICE.md](NOTICE.md).

---

## English

**Trasivo** is a mobile-first GPS route video maker. Upload a GPX, FIT or TCX file from one GPS-recorded activity and generate a video. The interface and on-video stats support Lithuanian and English.

### Usage

1. Open the published website in your browser.
2. Select **Choose a file**. If you need an activity file, open **Where do I get a file?**.
3. Upload a GPX, FIT or TCX file containing GPS coordinates.
4. Select **Generate video**, keep your screen on and wait for the download button.
5. Optional controls are available under **Settings**.

Extract ZIP archives before uploading. Apple Health XML, CSV, JSON and sharing links are not supported. An original activity FIT usually preserves more stats; a navigation-only GPX may contain no timestamps or heart-rate data.

### GitHub Pages

This is a static website; no dependency installation, build step or backend is needed.

Repository → **Settings → Pages → Deploy from a branch → main → /(root) → Save**.

The entry file is `index.html`. After deployment, the public HTTPS URL can be opened directly on a phone.

### Privacy and limitations

Activity files are read and videos are generated in the user’s browser. The app has no upload server or user accounts. Map imagery, fonts and libraries are fetched from third-party services, so an internet connection is required. The selected language is remembered on that device.

Keep the page open during video generation. Depending on the browser, the output is MP4 or WebM. Actual behaviour can vary across phones.

File-export instructions are available in the app and in [EXPORT_GUIDE.md](EXPORT_GUIDE.md).

The homepage photograph credit and external resources are listed in [NOTICE.md](NOTICE.md).
