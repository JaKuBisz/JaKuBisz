<h1 align="center">Hi, I'm Jakub 👋</h1>

<p align="center">
  <b>.NET engineer 🇨🇿</b><br>
  From code to hardware — and everything in between.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jakubkubisz/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://github.com/JaKuBisz?tab=repositories">
    <img src="https://img.shields.io/badge/Projects-181717?style=for-the-badge&logo=github&logoColor=white" alt="Projects">
  </a>
</p>

---

### About

- 🧑‍💻 **.NET developer.** I started with .NET before high school and had my first dev job before I finished it, working on a dispatch software for the Integrated Rescue System of Czechia.
- 🔍 **I like knowing how things work beyond my own code.** One month it's GPU kernels, another it's the networking in my homelab — if something around me breaks or interests me, I end up inside it.
- 🔧 **Most of my side projects start because something around me broke or annoyed me** — car diagnostics over OBD2, 3D printer firmware, BLE gadgets, home automation.
- 🏠 **I run my own homelab** — TrueNAS, Dockerized services - Immich, Nextcloud, Home Assistant, n8n workflows, the network, the backups. Keeping my stuff local. If I rely on it, I want to understand it.
- 💬 **Interested in** clean layered architecture, dependency injection, performance and parallelism, CI pipelines, and wiring the physical world into software.

---

### Tech I work with

**Core**

![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Blazor](https://img.shields.io/badge/Blazor-512BD4?style=flat-square&logo=blazor&logoColor=white)
![EF Core](https://img.shields.io/badge/EF_Core-512BD4?style=flat-square&logo=nuget&logoColor=white)
![SQL](https://img.shields.io/badge/SQL_Server_·_MySQL_·_PostgreSQL_·_SQLite-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![xUnit](https://img.shields.io/badge/xUnit-5E5E5E?style=flat-square&logo=xunit&logoColor=white)
![Autofac](https://img.shields.io/badge/Autofac-512BD4?style=flat-square&logo=nuget&logoColor=white)

**Tinkered with**

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**Tooling**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Home Assistant](https://img.shields.io/badge/Home_Assistant-41BDF5?style=flat-square&logo=homeassistant&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)

---

### Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/JaKuBisz/GpuBenchmarkingSuite">⚡ GpuBenchmarkingSuite</a></h4>
      <p>When is a GPU actually worth it? Turns out often it isn't: on a 64×64 matrix
      multiply the GPU came out 11× <em>slower</em> than a plain loop, because transfer
      cost dwarfs the arithmetic. Small and focused, but the numbers are honest, every
      variant is validated, and CI runs on every push. Practical part of my
      master's thesis.</p>
      <p><code>C#</code> <code>.NET 10</code> <code>ILGPU</code> <code>ComputeSharp</code> <code>xUnit</code> <code>GitHub Actions</code></p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/bambulab/BambuStudio/pull/12060">🖨️ BambuStudio upstream contribution</a></h4>
      <p>Open PR against Bambu Lab's slicer fixing third-party filaments being unusable in
      the AMS, and remaining weight never updating. Finding and fixing a real bug in a large
      unfamiliar C++ codebase.</p>
      <p><code>C++</code> <code>open source</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/JaKuBisz/OBD2AI">🚗 OBD2AI</a></h4>
      <p>Android app that reads live telemetry from your car's OBD2 port over Bluetooth and
      explains faults in plain language using an LLM, so <code>P0420</code> becomes something
      you can act on.</p>
      <p><code>Kotlin</code> <code>Bluetooth</code> <code>OpenAI API</code></p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/JaKuBisz/HashTrack">🏷️ HashTrack</a></h4>
      <p>Outlook add-in that adds hashtags to mail, calendar and tasks. Layered C#
      architecture with an Autofac container that registers services by scanning for
      attributes, so adding a service means adding an attribute and nothing else.
      Tag clustering compares digits exactly and text fuzzily, so
      <code>#invoice</code> and <code>#invoices</code> merge but <code>#Sprint1</code> and
      <code>#Sprint2</code> never do. My bachelor's thesis.</p>
      <p><code>C#</code> <code>VSTO</code> <code>WPF/MVVM</code> <code>Autofac</code> <code>Entity Framework</code> <code>SQLite</code></p>
    </td>
  </tr>
</table>

---

### Education

- 🎓 **Master's (Ing.), Managerial Informatics** — Silesian University in Opava, 2026.
  Thesis: *Parallelization of Computations Using Graphics Cards* →
  [**GpuBenchmarkingSuite**](https://github.com/JaKuBisz/GpuBenchmarkingSuite)
- 🎓 **Bachelor's (Bc.), Informatics** — VŠB – Technical University of Ostrava, 2024.
  Thesis: *Hashtag Plugin for MS Outlook* →
  [**HashTrack**](https://github.com/JaKuBisz/HashTrack)

---

<p align="center">
  <sub>Open to interesting problems, especially where .NET meets hardware or AI.</sub>
</p>
