# 📅 Schema Vecka 8: Agila Metoder & Git-Flow

Den här veckan fokuserar vi mindre på *vad* vi kodar och mer på *hur* vi jobbar tillsammans. Vi går från att vara ensamma utvecklare till att bli ett högpresterande team.

---

## 📅 Måndag: Git & Team-start

Vi lägger grunden för samarbetet. Hur delar vi kod utan att skapa kaos?

### Mål för dagen

* Behärska grundläggande Git-kommandon i grupp.
* Förstå Merge Conflicts och hur man löser dem.
* Skapa teamets gemensamma spelregler (Working Agreement).

### 🏋️ Eftermiddagsövning: "The Conflict Lab"

Gå samman i era grupper (4 personer).

1. **Repository-setup:** En person skapar ett repo och bjuder in de andra.
2. **Kollisionskurs:** Alla ska samtidigt försöka ändra på samma rad i en `README.md`, committa och pusha.
3. **Lösningen:** Träna på att dra ner ändringar, lösa konflikter lokalt och pusha upp igen.
4. **Working Agreement:** Skapa en fil i repot som heter `TEAM.md`. Skriv ner era tider, hur ni kommunicerar och vad som krävs för att ni ska vara nöjda med varandra på fredag.

---

## 📅 Tisdag: Agil Intro & GitHub Projects

Vi går från en att-göra-lista i huvudet till en visuell tavla.

### Mål för dagen

* Förstå agila värderingar (Individer framför processer).
* Sätta upp GitHub Projects för teamet.
* Skapa de första korten (Issues).

### 🏋️ Eftermiddagsövning: "Building the Board"

1. **Setup:** Skapa ett **GitHub Project** kopplat till ert team-repo.
2. **Från Idé till Kort:** Spåna fram 10 saker en webshop behöver (t.ex. "Logga in", "Visa produkter"). Skapa en Issue för varje sak.
3. **Prioritering:** Sortera korten i en "Backlog" efter vad som är viktigast.

---

## 📅 Onsdag: Scrum i Praktiken (User Stories)

Hur pratar vi om funktioner så att alla förstår?

### Mål för dagen

* Skriva User Stories med formatet: *"Som en [roll], vill jag [mål], så att [nytta]"*.
* Bryta ner stora krav (Epics) till hanterbara uppgifter (Tasks).
* Förstå rollerna: Scrum Master, Product Owner och Teamet.

### 🏋️ Eftermiddagsövning: "The User Story Workshop"

1. **Story Time:** Ta era Issues från igår och skriv om dem till riktiga User Stories.
2. **Defintion of Done (DoD):** För en av era stories, skriv ner exakt vad som krävs för att den ska kallas "klar" (t.ex. "Koden är pushad", "Linter går igenom", "Testad i Chrome").

---

## 📅 Torsdag: Git-Flow & Projektstart

Nu knyter vi ihop säcken. Hur kopplar vi det agila planerandet till den faktiska koden?

### Mål för dagen

* Behärska Branching Strategies (Feature branches).
* Skapa Pull Requests (PR) och genomföra Code Reviews.
* **PROJEKTSTART:** Ni får era instruktioner för slutprojektet.

### 🏋️ Eftermiddagsövning: "The PR-train"

Innan ni börjar med projektet, gör denna snabbövning:

1. Skapa en ny branch: `git checkout -b feature/test-name`.
2. Gör en ändring, pusha och skapa en **Pull Request** på GitHub.
3. En lagkamrat måste **Reviewa** och godkänna koden innan den får mergas.
4. **Koppla:** Lär er att skriva `Fixes #1` i er PR för att automatiskt stänga ett kort på projekt-tavlan.

---

## 📅 Fredag: Sprint 1 - Fullt fokus

Idag finns ingen föreläsning. Teamet äger sin tid.

### Mål för dagen

* Genomföra ett "Daily Stand-up" (15 min).
* Påbörja kodningen av projektets grundstomme.
* Fokusera på samarbete och att hjälpa varandra förbi hinder.

---

# 🚀 README: Slutprojekt "The Epic Store" (Gruppuppgift)

Här är instruktionerna för ert slutprojekt. Ni ska arbeta i team om 4 personer.

## 📝 Uppdraget

Ni ska bygga en modern, funktionell webbapplikation med **Next.js 16**, **Tailwind 4** och **Biome**. Appen ska hämta data från ett externt API och tillåta full CRUD-funktionalitet.

### Tekniska Krav

1. **Arkitektur:** Använd Server Components för datahämtning och Client Components för interaktivitet.
2. **URL State:** Sökning, filtrering eller sortering ska hanteras via `searchParams`.
3. **Data:** Ni ska kunna Läsa, Skapa, Uppdatera och Radera data mot ett API (t.ex. Platzi eller Supabase).
4. **Forms:** (Gås igenom måndag v.9) – Formulär ska användas för att skicka data.

## 🔄 Det Agila Arbetssättet (Krav för godkänt)

Det räcker inte att koden fungerar. Ni bedöms på hur ni har jobbat:

* **GitHub Projects:** Alla tasks ska finnas på tavlan. Inga tasks får "hänga" utan att vara kopplade till en person.
* **Branching:** Ingen kod pushas direkt till `main`. Allt går via `feature`-branches.
* **Code Reviews:** Varje Pull Request ska ha minst en godkänd review från en lagkamrat.
* **Commits:** Commits ska vara beskrivande och gärna referera till ett issue-nummer (t.ex. `git commit -m "feat: add login form, closes #4"`).

## 📅 Tidslinje

* **Vecka 8 (Torsdag-Fredag):** Planering, setup och första kodbasen.
* **Vecka 9 (Måndag):** Föreläsning Forms. Fortsatt jobb.
* **Vecka 9 (Fredag):** Slutdemo och "Sprint Review".
