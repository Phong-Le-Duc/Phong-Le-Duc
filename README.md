# 👋 Hej, jeg er Phong Le Duc

Frontend-udvikler med passion for moderne webteknologier, brugervenlighed og visuelt stærke løsninger.
Jeg er uddannet frontend-udvikler fra Roskilde Tekniske Skole og har samtidig opbygget grundlæggende back-end erfaring, hvilket giver mig en solid forståelse for hele webstacken.

Derudover har jeg en professionsbachelor i Digital Konceptudvikling, som styrker mit arbejde med brugeroplevelse, idéudvikling og digitale løsninger, der både fungerer teknisk og forretningsmæssigt.

---
Spring over, og gå til indhold
Du sagde:
made a link on netlify 

https://app.netlify.com/projects/magenta-pie-1a72a5/

how do i download the folder to my computer
ChatGPT sagde:
That link is the Netlify dashboard for your project — Netlify does not let you download the deployed site as a folder directly. Netlify is deployment-only, not storage.

How you download it depends on how the site was uploaded in the first place. Here are the correct scenarios 👇

✅ Case 1: You uploaded the folder from your own computer (most common)
Then Netlify does NOT have the original folder — you already do.

➡️ Check where you originally:

Drag-and-dropped the folder into Netlify
or

Ran netlify deploy
or

Connected GitHub

Netlify only keeps a compiled deploy, not your source project.

✅ Case 2: The site is connected to GitHub (BEST case)
This is the only case where you can truly “download the folder”.

Steps:
Go to your Netlify project

Click Site configuration

Go to Build & deploy

Look for Repository

If it shows a GitHub repo → click it

On GitHub:

Click Code

Choose Download ZIP

That ZIP = your full project folder ✅

⚠️ Case 3: You only have the deployed site (no Git, no local copy)
Netlify cannot give you a clean project folder.

What you can do (last resort):

Download the compiled site (HTML/CSS/JS only)

How:
Go to Deploys

Click the latest deploy

Click Download deploy

⚠️ Limitations:

No source files

No build tools

No original folder structure

React/Vite/etc will be flattened

🔑 Important truth (so you don’t lose work again)
Netlify is not a backup system.

Best practice:

Keep your project locally

Push to GitHub

Connect Netlify to GitHub

That way:

You can always re-download

You never lose your code

Netlify becomes “deploy only”

Next step
Tell me one thing:

Did you upload via GitHub, drag-and-drop, or CLI?

I’ll give you exact step-by-step instructions for your case.

Du sagde:
well i did it once directly on netlify and got the folder
ChatGPT sagde:
Got it 👍
Then you’re remembering “Download deploy” — that’s the only time Netlify gives you a folder back.

Here’s exactly how to do it again:

✅ How to download the folder from Netlify
Open your project in Netlify
👉 https://app.netlify.com/projects/magenta-pie-1a72a5/

In the left menu, click Deploys

You’ll see a list of deploys
→ Click the latest deploy (the one at the top)

On the deploy page, look for “Download deploy”
(usually top-right or under the ⋯ menu)

Netlify downloads a ZIP file

Unzip it on your computer → that’s the folder you got last time

⚠️ Very important limitation (this catches people)
The downloaded folder is:

✅ HTML / CSS / JS

❌ NOT your original project

❌ No source files (React, Vite, SCSS, etc.)

❌ No build config

It’s the built output, not the dev project.

So if you:

Uploaded a simple static site → you’re fine

Uploaded a React/Vite project → this is not editable source

🔒 Strong recommendation (so this doesn’t happen again)
Since you’re learning web dev:

Always keep a local copy + GitHub

your-project/
├─ src/
├─ index.html
├─ package.json
└─ README.md
Then:

GitHub = source of truth

Netlify = deployment only

If you want, I can:

Help you rebuild the project from the deploy

Or set you up with GitHub + Netlify the right way

Or tell you if your deploy ZIP is usable or not

Just tell me what kind of project it is (plain HTML? React? Vite?).

Du sagde:
-  **Javascript/TypeScript**
- **React**
- **Next.js**
- **Node.js** 
- **Tailwind CSS**
- **Vite**
- **ZOD** (formularhåndtering og validering)
- **State management** med React Hooks
- **Responsivt design**
- **Git & GitHub**
- **God kodekvalitet** (ESLint, Prettier)

det er min kompetence list. kan du sætte det i en orden der giver kronologisk mening+
ChatGPT sagde:
Ja 👍
Her er en kronologisk og pædagogisk rækkefølge, som både giver teknisk mening og læses rigtigt af arbejdsgivere (især junior frontend / web-stillinger i DK).

Jeg forklarer kort hvorfor rækkefølgen ser sådan ud — bagefter får du en færdig kompetenceliste, du kan copy-paste.

🧠 Den logiske lærings- og kompetencerækkefølge
1️⃣ Fundamentet (alt bygger på dette)
Disse er uundgåelige basisteknologier:

JavaScript / TypeScript
→ Sproget + typesystemet

2️⃣ Frontend framework & økosystem
Når sproget er på plads:

React
→ Komponenter, hooks, state, rendering

State management med React Hooks
→ useState, useEffect, useContext, custom hooks

3️⃣ Styling & UI
Når komponenter findes, skal de styles:

Tailwind CSS
→ Utility-first styling

Responsivt design
→ Mobile-first, breakpoints, layout

4️⃣ Build tools & moderne workflow
Hvordan projekter faktisk køres og bygges:

Vite
→ Dev server, bundling

5️⃣ Fullstack / framework ovenpå React
Når React er kendt, giver dette mening:

Next.js
→ Routing, SSR, API routes

6️⃣ Backend-forståelse
Ikke backend-heavy, men vigtigt:

Node.js
→ Runtime, scripts, simple APIs

7️⃣ Validering & formularer
Når data flyder mellem UI og backend:

ZOD (formularhåndtering og validering)

8️⃣ Kvalitet & samarbejde
Det der gør dig ansættelses-klar:

Git & GitHub
→ Version control, branches, PRs

God kodekvalitet
→ ESLint, Prettier

✅ Færdig kompetenceliste (klar til CV / LinkedIn)
Frontend & Web Development

JavaScript / TypeScript

React (Hooks & state management)

Tailwind CSS

Responsivt design

Frameworks & Tooling

Vite

Next.js

Node.js

Formularer & validering

ZOD

Kvalitet & samarbejde

Git & GitHub

ESLint & Prettier

💡 Tip (vigtigt)
Hvis du søger junior frontend-stillinger, så er denne rækkefølge meget stærk i DK — den signalerer:

Struktur

Forståelse

Produktionsklarhed

Hvis du vil, kan jeg også:

Tilpasse den til jobopslag

Lave en kort version (1-linje kompetencefelt)

Eller omskrive den til ”jeg kan…”-form til ansøgninger

Sig bare til 💪

Du sagde:
lav en samlet liste
ChatGPT sagde:
Selvfølgelig 👍
Her er én samlet, kronologisk kompetenceliste, ren og klar til CV / LinkedIn:

JavaScript / TypeScript

React

State management med React Hooks

Tailwind CSS

Responsivt design

Vite

Next.js

Node.js

ZOD (formularhåndtering og validering)

Git & GitHub

ESLint & Prettier

Hvis du vil, kan jeg også:

komprimere den til én linje

justere sproget til jobopslag

eller gøre den mere junior-venlig / realistisk

Bare sig til 👌

Du sagde:
kan man tilføje lite backend som prisma, postman lite sql eller hvad det hedder?
ChatGPT sagde:
Ja — helt klart ja 👍
Og det er faktisk en rigtig god idé for en juniorprofil, hvis det formuleres korrekt.

Nøglen er at kalde det “let backend / database-forståelse”, ikke fuld backend.

✅ Hvad giver mening at tilføje (og hvad de hedder korrekt)
✔️ Prisma
✔️ Meget relevant

ORM til Node.js / Next.js

Signalérer databaseforståelse uden at oversælge

Formulering:

Prisma (ORM)

✔️ SQL (lite)
Ja — men hold det simpelt og ærligt.

Formulering:

Grundlæggende SQL (CRUD)
eller

Relationelle databaser (grundlæggende SQL)

✔️ Postman
God idé, men det er et værktøj, ikke backend i sig selv.

Formulering:

Postman (API-test)

❌ “Postman Lite SQL”
Det findes ikke — du tænker sandsynligvis på:

SQLite (meget almindeligt med Prisma)

evt. PlanetScale / Supabase (men kun hvis du reelt har brugt dem)

🧠 Sådan placerer vi det korrekt i din liste
Vi indsætter det efter Node.js, så det giver kronologisk mening.

✅ Opdateret samlet kompetenceliste (realistisk & stærk)
JavaScript / TypeScript

React

State management med React Hooks

Tailwind CSS

Responsivt design

Vite

Next.js

Node.js

Prisma (ORM)

Grundlæggende SQL (CRUD)

Postman (API-test)

ZOD (formularhåndtering og validering)

Git & GitHub

ESLint & Prettier

⚠️ Vigtigt (det her gør forskellen i interviews)
Du bør kunne:

Forklare hvad Prisma gør (model → migration → query)

Forklare forskel på client/server i Next.js

Forklare hvad et API endpoint er

Ikke mere end det — og det er helt ok som junior.

Hvis du vil, kan jeg:

optimere listen specifikt til frontend vs fullstack junior

eller skrive en kort forklaring pr. punkt, så du er klar til interview

Sig til 💪

Du sagde:
lav en liste med ydmyg intro
ChatGPT sagde:
Perfekt 💡
Her er en ydmyg og professionel version af din kompetenceliste, som signalerer “jeg kan, men jeg er stadig lærende” — det passer rigtig godt til juniorstillinger:

Kompetencer
Jeg har erfaring med frontend- og webudvikling og arbejder løbende på at udvide mine færdigheder:

JavaScript / TypeScript

React

State management med React Hooks

Tailwind CSS

Responsivt design

Vite

Next.js

Node.js

Prisma (ORM)

Grundlæggende SQL (CRUD)

Postman (API-test)

ZOD (formularhåndtering og validering)

Git & GitHub

ESLint & Prettier

Hvis du vil, kan jeg lave en endnu kortere version på én linje, der passer perfekt til CV eller LinkedIn, uden at det virker arrogant.

Vil du, jeg gør det?

Du sagde:
grundlæggende viden:
og så liste af alt det backend vi har nævnt
ChatGPT sagde:
Perfekt! Her er en ydmyg “grundlæggende viden” sektion, kun med backend-relaterede ting, som vi har snakket om:

Grundlæggende viden
Jeg har grundlæggende viden inden for backend og databaser:

Node.js

Prisma (ORM)

Grundlæggende SQL (CRUD)

Postman (API-test)

Hvis du vil, kan jeg lave en samlet CV-kompetenceliste, hvor frontend og backend er opdelt med “Erfaring” og “Grundlæggende viden” — det ser rigtig professionelt ud til juniorstillinger.

Vil du, jeg gør det?

Du sagde:
hvad med mysql?
ChatGPT sagde:
Ja – helt klart, MySQL kan tilføjes som en del af din backend-kompetence. 💡

Hvis vi vil holde det ydmygt og realistisk, kan du skrive det sådan:

Grundlæggende viden
Jeg har grundlæggende viden inden for backend og databaser:

Node.js

Prisma (ORM)

MySQL (grundlæggende SQL / CRUD)

Postman (API-test)

💡 Tip: Hvis du bruger Prisma, kan du nemt koble til MySQL, så det hænger logisk sammen.

Hvis du vil, kan jeg lave en færdig CV-kompetenceliste, hvor frontend og backend er opdelt, inklusiv MySQL, som ser professionel og overskuelig ud. Skal jeg gøre det?

Du sagde:
relationele databaser tilføj?
ChatGPT sagde:
Perfekt 👍
Så kan vi formulere det mere generelt og stadig ydmygt ved at nævne relationelle databaser i stedet for kun MySQL, men stadig inkludere MySQL som eksempel.

Grundlæggende viden
Jeg har grundlæggende viden inden for backend og databaser:

Node.js

Prisma (ORM)

Relationelle databaser (MySQL, grundlæggende SQL / CRUD)

Postman (API-test)

Hvis du vil, kan jeg lave en samlet CV-kompetenceliste, hvor frontend og backend er opdelt pænt og professionelt, så du kan indsætte den direkte i dit CV eller LinkedIn.

Vil du, jeg gør det?

Du sagde:
vi lavede også javascript testin gpå et tidspunkt
ChatGPT sagde:
Ah perfekt! 💡
Så vi kan tilføje JavaScript-testning (unit tests / test frameworks) under grundlæggende viden eller backend-relaterede færdigheder — det giver rigtig godt indtryk for junior frontend/fullstack.

Her er en opdateret version:

Grundlæggende viden
Jeg har grundlæggende viden inden for backend, databaser og test:

Node.js

Prisma (ORM)

Relationelle databaser (MySQL, grundlæggende SQL / CRUD)

Postman (API-test)

JavaScript-testning (fx Jest / unit tests)

Hvis du vil, kan jeg lave en færdig samlet CV-kompetenceliste, hvor frontend og backend / test er opdelt, med alt vi har snakket om — klar til LinkedIn eller CV.

Skal jeg gøre det?

Du sagde:
jeg ved ik hvad det hedder vi lavede bare tests til vores egne koder
ChatGPT sagde:
Ah, perfekt, så det var altså egentlige små tests af din egen kode, men uden et formelt testframework som Jest eller Mocha. Det kan vi stadig formulere ydmygt og forståeligt, så det giver mening for en arbejdsgiver.

Her er en opdateret version af grundlæggende viden, som inkluderer det:

Grundlæggende viden
Jeg har grundlæggende viden inden for backend, databaser og kodekontrol:

Node.js

Prisma (ORM)

Relationelle databaser (MySQL, grundlæggende SQL / CRUD)

Postman (API-test)

JavaScript-kodetestning (egne små tests af funktionalitet)

💡 Tip: Formuleringen “egne små tests af funktionalitet” gør det ærligt og ydmygt, men viser samtidig, at du tænker på kvalitet og fejlkontrol.

Hvis du vil, kan jeg nu lave en komplet CV-kompetenceliste, hvor frontend og backend er opdelt, inklusiv denne test-oplevelse. Det vil blive klar til at indsætte i CV eller LinkedIn.

Vil du, jeg laver den?

Du sagde:
hører det under backed?
ChatGPT sagde:
Ikke nødvendigvis 🙂

Det afhænger lidt af hvad testen handlede om:

Hvis du testede funktioner i Node.js eller API’er, hører det under backend / server-side.

Hvis du testede React-komponenter eller frontend-funktionalitet, hører det under frontend / JavaScript generelt.

Hvis det var små tests af egen kode uanset hvor, kan man skrive det som “generel JavaScript-kodetestning”, uden at det placeres strikt under backend.

💡 Til junior-CV anbefaler jeg at holde det under “grundlæggende viden” eller frontend/backend samlet, men ikke nødvendigvis kun backend, så det ikke lyder for tungt.

Hvis du vil, kan jeg lave en opdateret komplet CV-kompetenceliste, hvor alt vi har snakket om (frontend, backend, databaser, test) er pænt opdelt og ydmygt formuleret.

Skal jeg gøre det?

Du sagde:
node.js viden er det under front eller backebd?
ChatGPT sagde:
Node.js hører klart under backend 🙂

💡 Kort forklaring:

Frontend = alt der kører i browseren: HTML, CSS, JavaScript/TypeScript, React, Tailwind, responsivt design osv.

Backend = alt der kører på serveren: Node.js, databaser, API’er, Prisma, serverlogik.

Så hvis du skriver et CV eller en kompetenceliste, placeres Node.js under backend / grundlæggende viden, ikke frontend.

Hvis du vil, kan jeg nu lave en komplet, kronologisk og opdelt liste med frontend og backend inklusiv alt vi har snakket om, klar til CV/LinkedIn.

Vil du, jeg gør det?

Du sagde:
## 💻 Mine kompetencer

-  **Javascript/TypeScript**
- **React**
- **State management** med React Hooks
- **Tailwind CSS**
- **Responsivt design**
- **Vite**
- **Next.js** 
- **ZOD** (formularhåndtering og validering)
- **Git & GitHub**
- **God kodekvalitet** (ESLint, Prettier)
- **JavaScript-kodetestning (egne små tests af funktionalitet)**
  <br>
  ##Grundlæggende backend og databaser viden:
-  **Relationelle databaser (MySQL, grundlæggende SQL / CRUD)**
-  **Node.js**
-  **Prisma (ORM)**
-  **Postman (API-test)**

kan du formatere det til github readme filen så det ser bedre ud?
ChatGPT sagde:
Ja! 👍
Her er en pæn og læsevenlig version til en GitHub README.md, med korrekt Markdown-formatering, overskrifter og lidt punktopstilling, så det ser professionelt ud:

## 💻 Mine kompetencer

Jeg har erfaring med frontend- og webudvikling og arbejder løbende på at udvide mine færdigheder:

### Frontend
- **JavaScript / TypeScript**  
- **React**  
- **State management** med React Hooks  
- **Tailwind CSS**  
- **Responsivt design**  
- **Vite**  
- **Next.js**  
- **ZOD** (formularhåndtering og validering)  
- **Git & GitHub**  
- **God kodekvalitet** (ESLint, Prettier)  
- **JavaScript-kodetestning** (egne små tests af funktionalitet)  

### Grundlæggende backend og databaser
- **Node.js**  
- **Prisma (ORM)**  
- **Relationelle databaser** (MySQL, grundlæggende SQL / CRUD)  
- **Postman (API-test)**  
💡 Tips til at gøre det endnu flottere i GitHub:

Du kan bruge emojis til at markere backend vs frontend:

⚡ Frontend

🗄️ Backend

Du kan lave kort beskrivelse under hvert punkt hvis du vil vise lidt mere om, hvad du kan med teknologien.

Hvis du vil, kan jeg lave en version med emojis, lidt beskrivelse og bedre visuel struktur, som virkelig skiller sig ud på GitHub README.

Vil du, jeg gør det?



Der er ikke valgt nogen filDer er ikke valgt nogen fil
ChatGPT kan tage fejl. Vi anbefaler at dobbelttjekke vigtig information. Se .


---

## 🚀 Udvalgte projekter

- [**Din Mægler** – Ejendomsmægler app](https://github.com/Phong-Le-Duc/dinmaegler-Phong-Le-Duc)  
  Moderne webapp med login, favoritfunktion, galleri, kontaktformular og meget mere.  
  **Desktop only**

- [**Phongs Cinema App** – Biograf projekt](https://github.com/Phong-Le-Duc/Phongs-cinema-app)  
  Biograf webapp med booking, brugerstyring, og moderne design.
  **Mobile only**

- [**Kitchen Staff Recruitment**](https://papaya-treacle-3ae853.netlify.app)  
  Rekrutteringsfirma for køkkenpersonale.  
  Lavet KUN med HTML og CSS, med fokus på responsivitet (desktop og mobil, ikke landscape på tablet).  
  Udarbejdet under grundforløbet, hvor andet værktøj endnu ikke var lært.
  
<!-- Tilføj flere projekter her hvis du ønsker -->

---

## 📫 Kontakt

- **Mail:** phongleduc@gmail.com
- **LinkedIn:** [linkedin.com/in/phong-le-duc](https://www.linkedin.com/in/phong-le-duc)

---

*Tak fordi du kigger forbi min GitHub!*
