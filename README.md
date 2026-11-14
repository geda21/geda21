<div align="center">

<img width="108" src="https://avatars.githubusercontent.com/u/271062331?v=4" alt="Geda Taye GitHub profile portrait" />

# GEDA TAYE — BUILT ON A PHONE.
### Self-taught Android & Web Developer · Independent Product Builder · Ethiopia 🇪🇹

**No laptop. No development team. A smartphone, thousands of iterations, and working software.**

**[Explore my visual story portfolio →](index.html)** · **[PINAXA evolution →](https://github.com/geda21/PINAXA/blob/main/EVOLUTION.md)**

[![NONOX · Google Play](https://img.shields.io/badge/NONOX-Live_on_Google_Play-34A853?style=for-the-badge&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.nonox.app)
[![JABAA Shop](https://img.shields.io/badge/JABAA-Shop_Live-167B5B?style=for-the-badge)](https://jabashop.store)
[![LinkedIn](https://img.shields.io/badge/Let's_Connect-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/geda-taye-a60b403ba)

</div>

---

## The story behind the repositories

I'm **Geda Taye**, a self-taught developer building Android and web products from Ethiopia.

My education has not been a collection of tutorials followed by a collection of certificates. It has been writing Java on an Android phone, debugging manifest errors, wrestling with library compatibility, testing features on the same device I use to develop, and making product decisions when ambitious ideas turned out to be difficult to maintain.

The projects below aren't interchangeable demos. They tell a story of **experimentation → implementation → failure → redesign → release**.

> **The early screenshots are as important to my story as the polished ones.** You can see where I struggled, what I tried, and what eventually shipped.

### A timeline of practical engineering

| Period | What I was doing | What I learned |
|:--|:--|:--|
| **May 2026** | Iterating on **PINAXA Guardian**, a much broader Android personal-security and AI-assistant prototype | Java build systems, Android permissions, camera pipelines, voice interactions, model integration, debugging |
| **Late May 2026** | Designing and rebuilding PINAXA's expressive robot faces, attention/emergency states, local command histories and camera-based detection interfaces | Stateful UI, custom views, voice input, sensor/camera experimentation |
| **Later in 2026** | Simplifying the PINAXA concept into a more focused personal safety app | Product scope, reliability, privacy-sensitive flows and practical usability |
| **September 2026** | Experimenting with **AgentBridge** and instruction-driven phone automation, including Fiverr navigation and task progress logs | Android interaction workflows, state tracking, automation and failure handling |
| **October 2026** | Publishing **NONOX** to Google Play | Native Android lifecycle, accessibility/device-admin constraints, release and distribution |
| **2026 and ongoing** | Building **JLab**, **JABAA Shop**, and **EthioDate** | Kotlin/Compose, offline data, Supabase, commerce, authentication and responsive web products |

*Dates are anchored in my archived screenshots and development records; not every older intermediate build still exists.*

---

## Chapter 01 · PINAXA — when I tried to build a guardian

**This story started before NONOX.**

My original PINAXA idea was not simply a red panic button. I worked on an Android security guardian with camera processing, voice commands, contextual responses, expressive robot faces, emergency states and offline-first ambitions.

I produced multiple source archives and app builds. Along the way I encountered Android manifest errors, missing ML Kit dependencies and model-download failures. I also got tangible interfaces running: custom animated faces, camera previews, command logs and emergency activation workflows.

I repeatedly changed the guardian's face — glowing eyes, minimal shapes, worried/attentive expressions and stronger red-alert states — searching for a character that made the system easier to understand.

**Then I made a hard product choice:** reduce the ambition. The later PINAXA focuses on intentional panic activation, duress configuration, emergency contacts, an event timeline and evidence access.

The older work matters because **I implemented and tested the larger experiment before choosing to simplify it**.

<div align="center">

[<img src="https://raw.githubusercontent.com/geda21/PINAXA/main/assets/pinaxa-hero.png" alt="Current PINAXA: actual panic screen, emergency timeline and protected evidence UI" width="100%"/>](https://github.com/geda21/PINAXA)

<sub>Current product — the streamlined Android safety experience.</sub>

</div>

**[Read the original PINAXA engineering journey →](https://github.com/geda21/PINAXA/blob/main/EVOLUTION.md)**

### What the actual PINAXA app shows

<p align="center">
  <img src="https://raw.githubusercontent.com/geda21/PINAXA/main/assets/home.webp" alt="PINAXA actual panic and duress screen" width="28%" />
  <img src="https://raw.githubusercontent.com/geda21/PINAXA/main/assets/event-timeline.webp" alt="PINAXA actual emergency timeline" width="28%" />
  <img src="https://raw.githubusercontent.com/geda21/PINAXA/main/assets/evidence-lock.webp" alt="PINAXA actual evidence authentication screen" width="28%" />
</p>

**Engineering details:** Java, Android components, foreground services, camera/voice experimentation, local data, emergency state machines, device permissions.

*Technical honesty: archived iterations include simulations and incomplete model assets. A running UI or test alert is not evidence of independently validated threat detection or guaranteed emergency dispatch.*

---

## Chapter 02 · NONOX — from experiments to a Google Play product

An app designed to help people control smartphone distractions. **NONOX is published on Google Play**, and it was developed through a phone-only Android workflow.

This is the project where my experience with system-level Android behavior became a product: app blocking, strict phone-lock sessions, Task Force focus restrictions, session control and statistics. I worked with accessibility behavior, device administration, boot/restart scenarios and responsive overlays.

<div align="center">

[<img src="https://raw.githubusercontent.com/geda21/nonox-android/main/assets/nonox-real-ui-showcase.png" alt="NONOX developer-supplied product showcase using its Android UI" width="100%" />](https://github.com/geda21/nonox-android)

**[Install on Google Play](https://play.google.com/store/apps/details?id=com.nonox.app)** · **[Explore real screenshots](https://github.com/geda21/nonox-android#inside-nonox--real-screenshots)**

</div>

### The recognition matters — but the work came first

**SaaS Hive's July 2026 Launch Sprint** listed NONOX **3rd among 52 participating founders**, and SaaS Hive published a [founder spotlight](https://blog.saashive.com/post/coding-420-hours-on-a-6-inch-phone-in-a-room-with-flickering-electricity-to-build-a-focus-app) on the smartphone development journey.

[![NONOX recognition at SaaS Hive](https://raw.githubusercontent.com/geda21/nonox-android/main/assets/nonox-saashive-launch-sprint-recognition.svg)](https://saashive.com/monthly-launch-sprint/past)

**Evidence:** [Launch Sprint archive](https://saashive.com/monthly-launch-sprint/past) · [Founder interview](https://blog.saashive.com/post/coding-420-hours-on-a-6-inch-phone-in-a-room-with-flickering-electricity-to-build-a-focus-app)

---

## Chapter 03 · AgentBridge — teaching the phone to carry out a task

I also experimented with instruction-driven Android agents, trying to make a mobile assistant navigate applications and report task progress instead of only answering questions.

One of my archived **September 2026** test screens shows AgentBridge attempting to open Fiverr, inspect gig statistics, track a sequence of actions, and return an end-of-task report.

This is an **engineering experiment**, not a claim that the agent achieved perfect autonomous reliability. The logged steps and task-complete status illustrate what the interface displayed; third-party statistics and execution correctness require separate verification.

**Skills explored:** screen-state observation, app navigation, action logging, workflow execution, session timeouts and user-facing progress reports.

---

## Chapter 04 · JLab — building the workspace I needed myself

When you build several products from one phone, you need to organize projects, tasks, notes, resources, files and plans in the same place.

**JLab** is a native Android personal workspace using **Kotlin, Jetpack Compose, Room and local-first storage**. It includes project workspaces, task tracking, notes, file storage, planning, calendar views, productivity insights and customization.

<div align="center">

[<img src="https://raw.githubusercontent.com/geda21/Jlab/main/assets/jlab-android-showcase.png" alt="JLab showcase composed from actual Android app captures" width="100%" />](https://github.com/geda21/Jlab)

[**Explore JLab's repository and source →**](https://github.com/geda21/Jlab)

</div>

---

## Chapter 05 · Businesses and connected experiences

**[JABAA Shop](https://jabashop.store)** — a real digital marketplace for ebooks and courses. Built with web technologies and Supabase, with customer journeys, purchase flows, local ETB options and international purchase links. [Repository](https://github.com/geda21/jabashop).

**[EthioDate](https://ethiodate.base44.app/)** — a mobile-first dating and social discovery platform, exploring public profile discovery, likes, matching, messaging, authentication and premium-access workflows. [Product showcase](https://github.com/geda21/Ethiodate).

These projects moved my work beyond Android utilities into **commerce, data-backed web applications and consumer-facing product design**.

---

## What I actually work with

| Native Android | Web & backend | Workflow |
|---|---|---|
| Java, Kotlin, Android SDK | HTML, CSS, JavaScript | Smartphone-first development |
| Accessibility & Device Admin | Supabase & SQL concepts | Real-device debugging |
| Camera, voice & sensors | Authentication and marketplace flows | GitHub & release iteration |
| Jetpack Compose, Room/SQLite | Netlify, responsive interfaces | Documentation & product testing |

### What I can build for clients

**Android applications** · **Business websites** · **Customer-facing platforms** · **Custom productivity tools** · **Mobile-first UI engineering**

I'm self-taught, but not theory-only. My public work includes **source code where appropriate, real screenshots, production links, historic experiments and honest limitations**.

<div align="center">

### Want to work together?

[![Connect on LinkedIn](https://img.shields.io/badge/Discuss_a_Project-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/geda-taye-a60b403ba)
[![GitHub](https://img.shields.io/badge/See_the_Code-GitHub-24292F?style=for-the-badge&logo=github)](https://github.com/geda21)

**Built on a phone. Tested in the real world. Still building.**

</div>
