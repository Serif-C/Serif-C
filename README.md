<h1 align="center">Hey, I'm Serif Cetinalp 👋</h1>
<p align="center">Full-stack developer & systems tinkerer based in Toronto, ON</p>

<p align="center">
  <a href="https://linkedin.com/in/serif-cetinalp"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:serifcetinalp@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" /></a>
</p>

---

### 🧑‍💻 About Me

I'm a CS grad (York University, Lassonde School of Engineering) who ended up loving the intersection of software architecture and game systems design. My favorite part of building anything is the moment a mechanic that only existed in my head turns into working code, that's basically my main hobby at this point. Give me a weird gameplay idea and I will not rest until it's simulated, balanced, and running in an engine.

I care a lot about *why* a system is built a certain way, not just that it works. That means SOLID principles, event-driven architecture over tangled dependencies, and separating data from behavior wherever I can. I split my time between full-stack web projects and Unity/C# systems work, and I'm always looking for the overlap between the two.

---

### 🔥 Currently Building: Bonkerzzz (Placeholder title, demo to be released soon)

A first-person, Unity 6 survivors-like inspired by *Megabonk* — built from scratch as a deep dive into real-time systems architecture rather than just "making a game."

**Why I'm building it:** I wanted a project that would force me to design real architecture under pressure — combat that has to feel instant, progression systems that have to stay balanced as they grow, and dozens of interacting subsystems (enemies, weapons, items, talismans) that all need to evolve independently without turning into spaghetti. Survivors-likes are deceptively perfect for this: simple on the surface, brutal on the backend if you don't structure it right.

**Scope & architecture highlights:**
- Strict separation between data definitions (ScriptableObjects) and runtime instances — new content gets configured, not coded
- A single centralized damage/combat resolver so every interaction in the game runs through one validated, testable path
- An event-driven messaging layer (`GameEvents`) that lets items, talismans, and UI react to gameplay without ever referencing the systems that caused it
- A shared-pool, tree-based progression system per weapon, replacing simple flat upgrades
- Currently extending the project with a planned backend leaderboard — PostgreSQL-backed persistence for user profiles and scores, pushing the project into full-stack territory

<p align="center">
  <img src="docs/media/bonkerzzz-combat.gif" width="45%" alt="Combat and hit feedback demo" />
  <img src="docs/media/bonkerzzz-bossfight.gif" width="45%" alt="Tutorial Boss fight demo" />
</p>

---

### 🛠️ Skills

**Languages**

![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**Frameworks & Libraries**

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=flat&logo=unity&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white)

---

### ⚡ Quick Facts

- I default to building the architecture first, then the feature — data vs. runtime, event buses, single-source-of-truth resolvers, you name it
- I use AI as a mentor, not a crutch — I get a task breakdown, then write and review the code myself so I actually understand every line
- Off the keyboard, I train calisthenics and recently achieved my first clean muscle-up
- My favorite kind of project is one where a "fun mechanic" idea has to survive contact with real system design

---

### 🚀 Highlighted Projects

| Project | Description | Tech |
|---|---|---|
| **[VentSpace](https://serif-ventspace.vercel.app/)** | Full-stack anonymous posting platform with comments, reactions, tag-based search, and an AI-powered support chatbot. Built and deployed end-to-end, including JWT auth and a relational data layer. | React, TypeScript, Node.js, Express, Prisma, PostgreSQL, JWT, OpenAI API |
| **[Tea Cafe Simulator](https://github.com/Serif-C/3D-Cozy-Tea-Cafe-Sim)** | A systems-and-tooling-focused simulation project — modular SOLID architecture, custom editor tooling, grid placement/collision validation, and object pooling that doubled concurrent agent capacity. | Unity, C#, FSM, ScriptableObjects, Object Pooling |
| **Bonkerzzz** *(in development, see above)* | First-person real-time simulation and combat framework with data-driven design, a centralized combat resolver, and event-driven subsystems. Backend leaderboard in progress. | Unity, C#, ScriptableObjects, Event-Driven Architecture |
| **[Developer Portfolio](https://serif-c.github.io/My-Portfolio/)** | Personal portfolio site with a custom-animated hero banner (CSS particle effects, keyframe transitions) and a responsive, filterable project UI. | React, TypeScript, TailwindCSS, Vite |

---

<p align="center"><em>Always down to talk systems design, Unity architecture, or full-stack builds — feel free to reach out.</em></p>
