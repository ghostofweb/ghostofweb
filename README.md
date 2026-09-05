<div align="center">
Sahiljeet Singh Kalsi
 
**Full-stack developer · Building with LLMs and agentic systems**
 
[![Portfolio](https://img.shields.io/badge/Portfolio-ghostofweb.vercel.app-0A0A0A?style=flat-square&logo=vercel&logoColor=white)](https://ghostofweb.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/sahiljeet-singh-kalsi-085844244/)
[![Email](https://img.shields.io/badge/Email-Say_hello-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:sahiljeetsinghkalsi@gmail.com)
 
</div>

 
I build web applications in TypeScript — React, Next.js, Node — and increasingly spend my time on the layer above the model: **agentic systems, harnesses, and generative AI in production**.
 
The part I find interesting isn't prompting. It's everything around it — tool-calling loops that don't spiral, retrieval that returns the right chunk, evals that catch a regression before a user does, and failure handling for a component that is non-deterministic by design. Most of the engineering in a good AI product lives there.
 
My background in psychology shapes what I choose to build. I'm drawn to conversational systems for mental health and social impact, and to the harder question underneath them: how people calibrate trust in what a model tells them, and what an interface owes a user when the answer might be wrong.
 
**Currently:** deepening on agent orchestration, RAG evaluation, and multi-step tool use.
 
## Selected work
 
**[Make Video Small](https://github.com/ghostofweb/makevideosmall)** — A desktop app that puts a real interface on AV1 encoding, so you get FFmpeg and Av1an results without the command line. Handles hardware-accelerated encoding on NVENC and AMF, inspects your machine and media to suggest sensible parameters, and runs batch queues. Everything stays local — no uploads. Ships as a signed NSIS installer with an auto-updater.
`Electron` `React 19` `TypeScript` `Python` `FFmpeg / Av1an` `Vite`
 
The interesting problem here was the seam between three runtimes: an Electron renderer talking over a locked-down IPC bridge to a main process, which in turn supervises long-running Python and FFmpeg subprocesses — streaming progress back without blocking the UI or leaking a process when a job is cancelled.
 
**[Gaberina](https://github.com/ghostofweb/Gaberina)** — Full-stack e-commerce built as three deployables: a storefront, an Express API, and a separate admin panel for product and order management. Covers the parts that are easy to hand-wave and annoying to actually ship — JWT auth, cart and order state, filtering and sort, Cloudinary image uploads, and live payments through Razorpay and Stripe.
`React` `Vite` `Node.js` `Express` `MongoDB` `Stripe / Razorpay`
 
**[CipherSprint](https://github.com/ghostofweb/CipherSprint)** — A typing test that measures WPM and accuracy in real time, with Google sign-in, a leaderboard, and charts tracking progress across sessions. Accuracy is scored per character against the source text — correct, incorrect, extra and missed are counted separately rather than collapsed into a single "wrong."
`React` `Vite` `Firebase (Auth + Firestore)` `Chart.js` `Tailwind`
[Live →](https://ciphersprint.vercel.app/)
 
## Working with
 
**AI/ML** &nbsp;&nbsp; LLM APIs · Agentic workflows & tool calling · RAG · Vector search · Prompt & eval tooling · NLP
 
**Languages** &nbsp;&nbsp; TypeScript · JavaScript · Python · Kotlin · C++
 
**Frontend** &nbsp;&nbsp; React · Next.js · Tailwind CSS · Three.js
 
**Backend** &nbsp;&nbsp; Node.js · Express · REST APIs · JWT auth
 
**Desktop** &nbsp;&nbsp; Electron · IPC bridging · electron-builder
 
**Data** &nbsp;&nbsp; PostgreSQL · MongoDB · Firebase
 
**Tooling** &nbsp;&nbsp; Git · Vite · Vercel · Postman

# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=ghostofweb&theme=dark&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=ghostofweb&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=ghostofweb&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)
