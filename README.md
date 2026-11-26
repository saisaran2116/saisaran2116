# <img src="./assets/section-icons/profile.svg" width="30" alt=""> Gaddanti Sai Saran

**SDE Intern** · Web & mobile · B.Tech CSE, SRM University–AP (2024–2028)

Two things I’ve built for fellow students are a campus event calendar and a CGPA tracker. I also work on voice interfaces. At Omnitrix, my teammate and I built a prototype that lets someone upload a medical report, read a summary, and ask a follow-up question out loud.

[Projects](#projects) · [Experience](#experience) · [Tech stack](#tech-stack) · [Hackathons](#hackathons) · [Connect](#connect)

<a name="projects"></a>

## <img src="./assets/section-icons/projects.svg" width="30" alt=""> Projects

| Build | What it does | Links |
| --- | --- | --- |
| **Campus Hub** | Organizers upload an event poster and review the extracted details. Once staff approve the listing, students can find it on the calendar and save it. | [Calendar](https://campus-hub-gamma-eight.vercel.app/) · [Code](https://github.com/saisaran2116/Campus-hub) |
| **Sanjeevan** | A healthcare prototype that brings report summaries, vitals, and a voice assistant into one dashboard. I built the responsive interface and connected it to the backend. | [Demo](https://sanjeevan-omega.vercel.app/) · [Code](https://github.com/AnuragTummapudi/Sanjeevani) |
| **KalCG** | A grade calculator for the Kalvium community. More than 300 members have used it to track their academic performance. | [Tracker](https://kalcg.netlify.app/) |

<details>
<summary>Build notes</summary>

- **Campus Hub** checks for scheduling conflicts even when an event runs past midnight. [Read the scheduling design](https://github.com/saisaran2116/Campus-hub/blob/main/LLD.md)
- **Sanjeevan** was a 24-hour build with Anurag Tummapudi. I built responsive components and connected them to the health-analysis backend.
- **KalCG** had a query form that returned HTTP 504s. I routed submissions directly to the Express API, added a ten-second timeout, and tested failure cases in Postman.

</details>

<a name="experience"></a>

## <img src="./assets/section-icons/experience.svg" width="30" alt=""> Experience

As an **SDE Intern**, I build web and mobile features from the screen through to the API. One part of that work I enjoy is tracing a failed request. On KalCG, a form submission could time out without telling the student what happened. I changed how the form reached the server and added an error message so the student knew when to try again.

<details>
<summary>Community roles</summary>

I contribute to open source through GirlScript Summer of Code and am an associate at Next Tech Lab at SRM University–AP.

</details>

<a name="tech-stack"></a>

## <img src="./assets/section-icons/tech-stack.svg" width="30" alt=""> Tech stack

I use React for web interfaces, React Native for mobile apps, and Node.js and Express for APIs. For voice features, I’ve worked with LiveKit and Gemini. Each icon below opens the corresponding documentation.

<table>
<tr>
<td width="50%" valign="top"><strong>Languages</strong><br>
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" title="JavaScript"><img src="./assets/signal/icons/javascript.svg" width="38" alt="JavaScript"></a> <a href="https://www.typescriptlang.org/docs/" title="TypeScript"><img src="./assets/signal/icons/typescript.svg" width="38" alt="TypeScript"></a> <a href="https://docs.python.org/3/" title="Python"><img src="./assets/signal/icons/python.svg" width="38" alt="Python"></a> <a href="https://isocpp.org/" title="C++"><img src="./assets/signal/icons/cpp.svg" width="38" alt="C++"></a> <a href="https://www.postgresql.org/docs/current/tutorial-sql.html" title="SQL"><img src="./assets/signal/icons/sql.svg" width="38" alt="SQL"></a>
</td>
<td width="50%" valign="top"><strong>Web and mobile</strong><br>
<a href="https://react.dev/" title="React"><img src="./assets/signal/icons/react.svg" width="38" alt="React"></a> <a href="https://reactnative.dev/docs/getting-started" title="React Native"><img src="./assets/signal/icons/react-native.svg" width="38" alt="React Native"></a> <a href="https://nextjs.org/docs" title="Next.js"><img src="./assets/signal/icons/next-js.svg" width="38" alt="Next.js"></a> <a href="https://vite.dev/guide/" title="Vite"><img src="./assets/signal/icons/vite.svg" width="38" alt="Vite"></a> <a href="https://tailwindcss.com/docs" title="Tailwind CSS"><img src="./assets/signal/icons/tailwind-css.svg" width="38" alt="Tailwind CSS"></a>
</td>
</tr>
<tr>
<td width="50%" valign="top"><strong>Backend APIs</strong><br>
<a href="https://nodejs.org/en/docs" title="Node.js"><img src="./assets/signal/icons/node-js.svg" width="38" alt="Node.js"></a> <a href="https://expressjs.com/" title="Express"><img src="./assets/signal/icons/express.svg" width="38" alt="Express"></a> <a href="https://developer.mozilla.org/en-US/docs/Web/HTTP" title="REST APIs"><img src="./assets/signal/icons/rest-apis.svg" width="38" alt="REST APIs"></a> <a href="https://www.prisma.io/docs" title="Prisma"><img src="./assets/signal/icons/prisma.svg" width="38" alt="Prisma"></a>
</td>
<td width="50%" valign="top"><strong>Databases</strong><br>
<a href="https://www.postgresql.org/docs/" title="PostgreSQL"><img src="./assets/signal/icons/postgresql.svg" width="38" alt="PostgreSQL"></a> <a href="https://www.mongodb.com/docs/" title="MongoDB"><img src="./assets/signal/icons/mongodb.svg" width="38" alt="MongoDB"></a> <a href="https://dev.mysql.com/doc/" title="MySQL"><img src="./assets/signal/icons/mysql.svg" width="38" alt="MySQL"></a> <a href="https://supabase.com/docs" title="Supabase"><img src="./assets/signal/icons/supabase.svg" width="38" alt="Supabase"></a> <a href="https://firebase.google.com/docs" title="Firebase"><img src="./assets/signal/icons/firebase.svg" width="38" alt="Firebase"></a>
</td>
</tr>
<tr>
<td width="50%" valign="top"><strong>AI and speech</strong><br>
<a href="https://docs.livekit.io/" title="LiveKit"><img src="./assets/signal/icons/livekit.svg" width="38" alt="LiveKit"></a> <a href="https://ai.google.dev/gemini-api/docs" title="Gemini"><img src="./assets/signal/icons/gemini.svg" width="38" alt="Gemini"></a> <a href="https://alphacephei.com/vosk/" title="Vosk"><img src="./assets/signal/icons/vosk.svg" width="38" alt="Vosk"></a>
</td>
<td width="50%" valign="top"><strong>Tools and hosting</strong><br>
<a href="https://git-scm.com/doc" title="Git"><img src="./assets/signal/icons/git.svg" width="38" alt="Git"></a> <a href="https://docs.github.com/" title="GitHub"><img src="./assets/signal/icons/github.svg" width="38" alt="GitHub"></a> <a href="https://docs.docker.com/" title="Docker"><img src="./assets/signal/icons/docker.svg" width="38" alt="Docker"></a> <a href="https://learning.postman.com/" title="Postman"><img src="./assets/signal/icons/postman.svg" width="38" alt="Postman"></a> <a href="https://vercel.com/docs" title="Vercel"><img src="./assets/signal/icons/vercel.svg" width="38" alt="Vercel"></a> <a href="https://docs.netlify.com/" title="Netlify"><img src="./assets/signal/icons/netlify.svg" width="38" alt="Netlify"></a> <a href="https://render.com/docs" title="Render"><img src="./assets/signal/icons/render.svg" width="38" alt="Render"></a>
</td>
</tr>
</table>

<a name="hackathons"></a>

## <img src="./assets/section-icons/hackathons.svg" width="30" alt=""> Hackathons

I’ve taken part in **10+ hackathons** and reached **six finals**. Our teams earned runner-up at Omnitrix and CodeFusion. At Web3SSH, we finished in the top 10 with Rescu3, an Ethereum hardware wallet recovery project.

<details>
<summary>Event results</summary>

| Event | Our build | Result |
| --- | --- | --- |
| Omnitrix | Sanjeevan, a voice-enabled healthcare prototype | Runner-up |
| CodeFusion · RD Conclave 2026 | Real-time patient care | Runner-up |
| Web3SSH | Rescu3, an Ethereum hardware wallet recovery project | Top 10 teams |
| ETHGlobal Mumbai | An Ethereum-based project | Participant |

</details>

<a name="connect"></a>

## <img src="./assets/section-icons/connect.svg" width="30" alt=""> Connect

I’d love to hear from people building student tools or experimenting with voice interfaces. If you’ve tried one of my projects, tell me what you used it for and what could work better.

<a href="mailto:gaddantisaisaran@gmail.com"><img src="./assets/signal/email-link.svg" width="31%" alt="Email — Start a conversation"></a>
<a href="https://www.linkedin.com/in/sai-saran-gaddanti/"><img src="./assets/signal/linkedin-link.svg" width="31%" alt="LinkedIn — Connect with me"></a>
<a href="https://github.com/saisaran2116?tab=repositories"><img src="./assets/signal/github-link.svg" width="31%" alt="GitHub — Browse my work"></a>

<details>
<summary>Start an email about a project or opportunity</summary>

[Discuss a project](mailto:gaddantisaisaran@gmail.com?subject=Project%20collaboration) · [Discuss an internship](mailto:gaddantisaisaran@gmail.com?subject=Internship%20opportunity)

</details>
