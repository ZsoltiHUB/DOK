---
title: "A Programom - Részletes Terv 📋"
date: 2025-06-04T12:00:00+02:00
weight: 1 # Post order weight (lower numbers appear first)
# aliases: ["/program-reszletes"] # Alternative URLs that redirect to this post
tags: ["program", "tervek", "DÖK"] # Tags for categorization and filtering
categories: ["programok"] # Categories for broader classification
author: "Kis Zsolt" # Post author name

# Table of Contents settings
showToc: true # Show table of contents
TocOpen: false # Whether TOC is expanded by default

# Post status and visibility
draft: false # Set to true to hide post from public site
hidemeta: false # Hide post metadata (date, author, etc.)
comments: false # Enable/disable comments (if comment system is configured)

# SEO and meta information
description: "Részletes programterv a DÖK elnökségre - minden program leírással és megvalósítási tervvel."
canonicalURL: "https://kukievo.hu/posts/a-programom/" # Canonical URL for SEO
keywords: ["program", "DÖK", "diákönkormányzat", "tervek", "projektek"] # SEO keywords

# Code highlighting settings
disableHLJS: false # Disable Hugo's built-in syntax highlighting

# Social sharing and discovery
disableShare: false # Hide social share buttons (controlled by site config ShowShareButtons)
searchHidden: false # Hide from site search results

# Reading experience settings
ShowReadingTime: true # Display estimated reading time
ShowBreadCrumbs: true # Show breadcrumb navigation
ShowPostNavLinks: true # Show previous/next post navigation
ShowWordCount: true # Display word count
ShowRssButtonInSectionTermList: true # Show RSS button in lists
UseHugoToc: true # Use Hugo's built-in table of contents
hideSummary: false # Hide post summary/excerpt in lists

# Cover image configuration
cover:
    image: "/images/program-cover.jpg" # Cover image path (relative to static folder)
    alt: "Programterv áttekintés" # Alternative text for accessibility
    caption: "Részletes programok és projektek" # Caption text below image
    relative: false # Set to true when using page bundles with local images
    hidden: true # Hide cover image on single post page (show only in lists)

# Post editing configuration (for GitHub integration)
editPost:
    URL: "https://github.com/ZsoltiHUB/DOK/tree/main/content" # Base URL for edit links
    Text: "Elírás? Kiegészítenéd? - Javaslat változtatásra" # Text for edit link button
    appendFilePath: true # Append file path to edit URL for direct GitHub editing
---

<!-- Countdown Timer for Voting Day -->
<div style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white; padding: 20px; border-radius: 10px; text-align: center; margin-bottom: 30px; box-shadow: 0 4px 15px rgba(0,0,0,0.2);">
  <h2 style="margin: 0 0 15px 0; font-size: 1.5em;">⏰ Szavazás Napja</h2>
  <div id="countdown" style="font-size: 2em; font-weight: bold; margin: 10px 0;">
    <span id="days">0</span> nap 
    <span id="hours">0</span> óra 
    <span id="minutes">0</span> perc 
    <span id="seconds">0</span> másodperc
  </div>
  <p style="margin: 10px 0 0 0; opacity: 0.9;">🗳️ Június 10, 2025 - 14:00 (suli után)</p>
</div>

<script>
// Countdown Timer Script
function updateCountdown() {
    // Set the voting day date and time (June 10, 2025 at 8:00 AM)
    const votingDay = new Date('2025-06-10T14:00:00+02:00').getTime();
    const now = new Date().getTime();
    const distance = votingDay - now;

    // Calculate time units
    const days = Math.floor(distance / (1000 * 60 * 60 * 24));
    const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    const seconds = Math.floor((distance % (1000 * 60)) / 1000);

    // Display the countdown
    document.getElementById('days').textContent = days;
    document.getElementById('hours').textContent = hours;
    document.getElementById('minutes').textContent = minutes;
    document.getElementById('seconds').textContent = seconds;

    // If countdown is finished
    if (distance < 0) {
        document.getElementById('countdown').innerHTML = "🎉 SZAVAZÁS NAPJA! 🎉";
    }
}

// Update countdown every second
setInterval(updateCountdown, 1000);

// Initial call
updateCountdown();
</script>

# Programok

Mindegyik programhoz képviselők lesznek kijelölve a szervezés és lebonyolítás érdekében.  
Célom, hogy minél több program megvalósuljon a felső tagozat számára is.

## Fix Programok

### 📚 Osztályok Között Kahoot
Interaktív kvízjáték az osztályok közötti verseny szellemében.

### 🎵 Gimi: Zenei Stílusok Sorsolása Osztályonként
Minden osztály sorsolással kap egy zenei stílust, amely köré tematikus programokat szervezhetnek.

### 🏫 Áltsuli: Korcsoportos Programok
- **8-10-ig**: Sportprogramok
- **10 órától az osztálytermekben**: Mesék kisorsolása, a terem berendezése

### 🏃‍♂️ SPORTNAP
Infó lentebb

---

## Saját Programjaim

### 🎲 Társasjátékterem
Különböző társasjátékok behozása és közös játék lehetősége.

### 🐍 Állatsimogató
**Szervező**: M. Edina + további önkéntesek  
Egy terem ahol hallhattok egy kicsit a kígyókról és tartásukról (meg ha más állat akkor az is).  Általános tudnivalók a fajról és ismérveiről, csak nektek csak most.  
És ha nagyon jól viselkedtek, akár nyakba is vehető.  

### 🎬 MOZI: 4K-s TV-n Film/Sorozat
Valamilyen filmet vagy sorozatot letöltünk, esetleg szavazással választjuk ki.

### 🥤 Frissítő Pont → Hűtött Üdítők
Mindenki hozhatna be egy üdítőt, amit egy iskolai hűtőben lehűtenénk, és aki megszomjazna a sportolás közben vagy a nyári nap hőségében egy hideg üdítőre vágyik, annak biztosítjuk ezt a lehetőséget.

### ⛏️ Minecraft Verseny
Ahogy tavaly volt - népszerű építési és survival kihívások.

### 🎮 Játékterem – Többjátékos Videojátékok a TV-n
Különböző többjátékos játékok nagy képernyőn (részletek az lejjebb).

### 🎒 No Backpack Day RELOADED → Jutalom?
A tavalyi "no backpack day" felújított változata, most jutalommal a motiváció növelése érdekében.

### 🎵 Zene Kívánságműsor
Hasonlóan, mint tavaly - diákok zenei kívánságainak teljesítése.

### 👨‍🏫 Tanárkvíz
Játék, ahol a tanárok elárulnak magukról olyan információt, amit nem sokan tudhatnak, de nem privát. Ezeket összegyűjtjük, és a diákok feladata lesz az információkat a tanárokkal párosítani.

### 📱 Clash Royale / Brawl Stars / Más Mobilos Játék Verseny
Ha megoldható a technikai háttér - mobilos játékok versenye különböző kategóriákban.

---

## Részletes Leírások

### Sportnap🏃‍♂️
Röpi-Foci  
Röpi: tesiteremben két harmadban  
Foci: kinn  
osztályonként 1-1 csapat  
foci - 8 fő  
tesitanárok managelnek - Köszönjük!  

### 🎲 Társasjátékterem
Behozunk különböző társasjátékokat, hogy a diákok kipróbálhassák őket és együtt játszhassanak.

### 🐍 Állatsimogató
M. Edina be tudja hozni a kígyóját, esetleg más diákok is hozhatnak háziállatokat (előzetes engedélyeztetés után).

### 🎬 MOZI
4K-s TV-n vetítünk filmet vagy sorozatot. A műsort előzetesen szavazással választjuk ki a diákok között. (A felsősöknek külön mozi??)

### 🥤 Frissítő Pont
Mindenki hozzon be egy üdítőt, amit ha megengedik, egy iskolai hűtőben lehűthetünk. Aki szomjas, az ihat belőle.

### ⛏️ Minecraft Verseny
A tavalyi sikeres Minecraft verseny folytatása különböző kihívásokkal.  

### 🎒 No Backpack Day RELOADED
A tavalyi "no backpack day" újragondolt változata, most jutalommal, hogy legyen motiváció a részvételhez.

### 🎵 Zene Kívánságműsor
Hasonlóan a tavalyi évhez - diákok zenei kívánságainak lejátszása szünetekben vagy programok alatt. Előzetes szavazás alapján.

### 👨‍🏫 Tanárkvíz
Interaktív játék, ahol a tanárok elárulnak magukról egy-egy érdekes információt, amit nem sokan tudhatnak, de nem privát jellegű. A diákok feladata ezeket az információokat a megfelelő tanárokkal párosítani.

### 📱 Mobilos Játék Versenyek
Clash Royale, Brawl Stars és más mobilos játékok versenye - ha megoldható a technikai háttér biztosítása.

### 🎮 Játékterem (engedélyeztetés alatt)
Többjátékos videojátékok nagy TV-n való játszása.  
A tanulók saját (vagy előre behozott) kontrollerrel csatlakozhatnak, és 4K tévén ((amiket idén szereltek be egyes osztálytermekbe)) játszhatnak népszerű, akár 8 főt támogató videojátékokkal (pl. Super Smash Bros, Mario Kart). Szórakoztató, közösségépítő program minden korosztály számára.

Megvalósítási terv:  
A terembe beviszem a saját PC-met, amit HDMI-kábellel rákötünk az osztályterem tévéjére. A gépen előre feltelepített, többjátékos játékokat fogunk futtatni, amelyek támogatják a helyi (local) többfős játékot akár 8 játékos számára is – például **Super Smash Bros. Ultimate**, **Mario Kart** vagy **Overcooked!**.  
A diákokat (osztálytársak/évfolyamtársak) előzetesen megkérjük, hogy hozzanak magukkal kontrollert (PS5/4, Xbox, stb.), amit USB-n vagy Bluetooth-on keresztül tudunk csatlakoztatni a géphez. (Összesen 4-10 kontroller kéne)  
(Opcionálisan: A pontos játékválasztásról előre készítünk egy Forms-kérdőívet, ahol a tanulók szavazhatnak, hogy mely játékokat szeretnék játszani az eseményen.)  
Körönként 4–8 fő tud majd játszani, a kontrollereket pedig váltogatjuk a résztvevők között. (Több kontrollert is viszünk tartalékba, arra az esetre, ha valamelyik lemerül vagy nem működik megfelelően.)  
A program közösségépítő, szórakoztató és jól leköti a különböző évfolyamokból érkező tanulókat is.

---

*Minden program megvalósítása a diákok igényei és az iskola lehetőségei szerint alakul. A részleteket közösen dolgozzuk ki!*
