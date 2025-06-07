---
title: "A Programom"
date: 2025-06-04T10:00:00+02:00
draft: false
weight: 1
---

# A Programom - **Rövid Áttekintés**

<!-- Countdown Timer for Voting Day -->
<div style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white; padding: 20px; border-radius: 10px; text-align: center; margin-bottom: 30px; box-shadow: 0 4px 15px rgba(0,0,0,0.2);">
  <h2 style="margin: 0 0 15px 0; font-size: 1.5em;">⏰ Szavazás Napja</h2>
  <div id="countdown" style="font-size: 2em; font-weight: bold; margin: 10px 0;">
    <span id="days">0</span> nap 
    <span id="hours">0</span> óra 
    <span id="minutes">0</span> perc 
    <span id="seconds">0</span> másodperc
  </div>
  <p style="margin: 10px 0 0 0; opacity: 0.9;">🗳️ Június 10, 2025 - 14:00</p>
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

Itt találod a kampányom legfontosabb programjait és ötleteit. 

## 🎯 Főbb Programkategóriák

### 📚 Fix Programok
- **Osztályok között Kahoot** - Interaktív kvízverseny
- **Zenei stílusok sorsolása** (Gimi)  
- **Korcsoportos programok** (Áltsuli)
- **Sportnap** (K. Emilio + P. Viktor szervezésében)

### 🎮 Saját Programjaim
- 🎲 **Társasjátékterem**
- 🐍 **Állatsimogató** (M. Edina vezetésével)
- 🎬 **Mozi 4K TV-n**
- 🥤 **Frissítő pont** - hűtött üdítők
- ⛏️ **Minecraft verseny**
- 🎮 **Játékterem** - többjátékos videojátékok
- 🎒 **No Backpack Day RELOADED**
- 🎵 **Zene kívánságműsor**
- 👨‍🏫 **Tanárkvíz**
- 📱 **Mobilos játék versenyek**

---

## 📋 Részletes Program Leírások

**[🔗 Itt találod a teljes, részletes programtervet!](/posts/a-programom/)**

A fenti linken megtalálod minden program részletes leírását, megvalósítási tervét és gyakorlati részleteit.

---

