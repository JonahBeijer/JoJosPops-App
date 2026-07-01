# JoJosPops - Mobile Application (Frontend)

**JoJosPops** is een mobiele applicatie ontworpen voor de underground en pop-up scene, zoals car meets, raves en bush parties. Het platform lost het probleem op van vindbaarheid en gecontroleerde toegang binnen deze communities. 

De belangrijkste feature van de app is de **Delayed Location Reveal**: organisatoren maken een evenement aan waarbij bezoekers op de kaart eerst alleen een globale indicatie zien. De exacte locatie en marker worden pas via de API vrijgegeven en op de kaart getoond zodra de ingestelde begintijd is bereikt[cite: 2, 3].

---

## Kenmerken & Functionaliteiten (MVP)

Binnen deze MVP zijn de volgende kernfuncties gerealiseerd en functioneel getest[cite: 2, 3]:
* **Interactieve Kaart:** Integratie met Google Maps API voor een overzicht van pop-up events in de buurt[cite: 2, 3].
* **Delayed Location Reveal:** Client-side timers en dynamische marker-rendering op basis van API-timestamps[cite: 2, 3].
* **Gelaagde Toegang:** Ondersteuning voor openbare, 'on aanvraag' (request) en 'alleen op uitnodiging' (invite-only) evenementen[cite: 2, 3].
* **Veiligheidsindicatoren:** Direct inzichtelijk of er BHV/eerste hulp of beveiliging aanwezig is op het event[cite: 2, 3].
* **Premium Functies:** Geïntegreerde logica voor premium-gebruikers, zoals vroege locatietoegang[cite: 2, 3].

---

## Technische Stack

* **Framework:** React Native (Expo Workflow)
* **Taal:** TypeScript
* **Kaarten:** React Native Maps (Google Maps SDK)

---

## Installatie & Lokale Setup

Volg deze stappen om de frontend lokaal op te starten in een ontwikkelomgeving:

### 1. Systeemvereisten
Zorg ervoor dat de volgende software op de machine is geïnstalleerd:
* **Node.js** (LTS-versie)
* **npm** of **yarn**
* **Expo Go** app op een smartphone (voor testen op een fysiek apparaat) of een geconfigureerde simulator (iOS/Android).

### 2. Repository Klonen
```bash
git clone [https://github.com/JonahBeijer/JoJosPops-App.git](https://github.com/JonahBeijer/JoJosPops-App.git)
cd JoJosPops-App
