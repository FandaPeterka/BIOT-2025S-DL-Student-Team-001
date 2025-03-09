# BIOT-2025S-DL-Student-Team-001

## 📌 O projektu

SimpleGuard je aplikace určená pro monitorování objektů pomocí IoT technologie. 
Systém je postaven na mikrokontroléru HARDWARIO Core Module s akcelerometrem připevněným ke dveřím,
který detekuje neoprávněné manipulace.

## 👥 Složení týmu

🔹 Projektový manažer: Marek Ostrihoň
🔹 Backend: Simon Kristín, Tomáš Trnečka
🔹 Frontend: Anastasie Zdárská, František Peterka
🔹 Hardware: Hazar Yasin Sezgin
🔹 Dokumentace: Filip Smejhl

## 🛠 Použité technologie

Backend: Node.js (Express.js), MongoDB

Frontend: React.js

Hardware: HARDWARIO Core Module

Komunikace: MQTT / HTTPS

## 🚀 Hlavní vlastnosti

📡 Sběr dat z akcelerometru umístěného na dveřích

🔔 Detekce neoprávněných pohybů a odesílání upozornění

🌐 Zpracování a vizualizace dat v cloudové aplikaci

🛠 Možnost rozšíření o další senzory HARDWARIO

## 🏗 Architektura řešení

IoT node (Core Module) →→MQTT→→ Gateway (Radio Dongle) →→HTTP→→ Backend (Node.js) →→HTTP→→ Frontend (Next.js) 

## 📅 Milníky projektu
<div>
 <img src="/BIOT.png" width="400px">
</div>

**Aktuálně se nacházíme ve čtvrtém týdnu.**

🎨 Design

| **Code** | **Description** |
| M1 | Business Requests ⇒ Popsání klíčových User Stories  |
| M2 | Business Model ⇒ Popis aktérů, produktů a klíčových BUCs |
| M3 | Application Model ⇒ Návrh klíčových koncových bodů a schémat (datový model)  |
| M4 | Application Model ⇒ Návrh technického řešení IoT části (IoT node + gateway)  |
| M5 | Application Model ⇒ Základní návrh frontend rozhraní  |
| M6 | Application Model ⇒ Základní návrh frontend komponent  |

💻 Vývoj

| **Code** | **Description** |
| M1 | Vytvoření projektu a první commit v Git  |
| M2 | Implementace backendu  |
| M3 | Implementace IoT nodu a gateway  |
| M4 | Implementace frontendu  |
| M5 | Nasazení aplikace do cloudu  |

