# 👨‍💻 About Me

•⁠  ⁠Software engineer at *Palo Alto Networks*, previously at *Fidelity*
•⁠  ⁠I build systems that read messy real-world documents, check them, and leave a record you can trust
•⁠  ⁠Focused on multi-tenant data isolation, AI security, and document and speech AI for languages most tools ignore
---

## 🛠️ What I've Built

**Document verification engine** · *Python, FastAPI, PostgreSQL 16, Next.js*
- Reads every page of a shipment or corporate file with two independent readers, checks it against rule packs written in YAML with a cited source for every rule, and has a person confirm each point before a one-page report is signed
- Tenant isolation enforced by Postgres row-level security, least-privilege database roles, and a hash-chained audit log that stores ids and fingerprints, never document values
- Retention with deletion certificates, encrypted and signed backups verified by a real restore, and a CI gate that runs the previous release against every new schema
- Offline-first phone app: a guided camera that checks sharpness, light and glare before taking the picture, and an outbox that survives dropped connections page by page
- ~32,000 lines, ~800 automated tests

**LLM security** · *Python*
- A stateless SDK that scores prompts for jailbreaks and prompt injection and returns a risk score, a block decision and the scanners that fired
- A red-team framework for RLS-protected vector databases: 7+ attack types (prompt injection, data exfiltration, privilege escalation), multi-tenant isolation tests, Prometheus and Grafana metrics
- Research notebook on adversarial attacks against transformer models

**Voice and archives** · *Python, OCR, speech recognition*
- A voice-to-document platform: staff speak in the field, it drafts a structured report for a person to review and sign
- A reader for scanned early-1900s government gazettes that fills in fields, shows the exact piece of the page each value came from, and scores itself against a hand-written answer key

**Systems** · *C*
- A Unix shell with job control and signal handling
- A memory allocator (`malloc`/`free`) built from scratch

---

## 🧰 Tech Stack

<table>

  <!-- LANGUAGES -->
  <tr>
    <td><strong>Languages</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" />
      <img src="https://img.shields.io/badge/SQL-336791?logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/C-00599C?logo=c&logoColor=white" />
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" />
      <img src="https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white" />
    </td>
  </tr>

  <!-- BACKEND & FRAMEWORKS -->
  <tr>
    <td><strong>Backend & Frameworks</strong></td>
    <td>
      <img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white" />
      <img src="https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB" />
      <img src="https://img.shields.io/badge/LlamaIndex-6B46C1" />
      <img src="https://img.shields.io/badge/Playwright-2EAD33?logo=playwright&logoColor=white" />
    </td>
  </tr>

  <!-- INFRASTRUCTURE -->
  <tr>
    <td><strong>Infrastructure</strong></td>
    <td>
      <img src="https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/AWS-232F3E?logo=amazon-aws&logoColor=white" />
      <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" />
      <img src="https://img.shields.io/badge/Linux%20%2F%20systemd-000000?logo=linux&logoColor=white" />
      <img src="https://img.shields.io/badge/Caddy-1F88C0?logo=caddy&logoColor=white" />
      <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white" />
    </td>
  </tr>

  <!-- SECURITY & AI -->
  <tr>
    <td><strong>Security & AI</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Row--Level%20Security-336791" />
      <img src="https://img.shields.io/badge/LLM%20Security-B91C1C" />
      <img src="https://img.shields.io/badge/OCR%20%26%20Speech-4B5563" />
      <img src="https://img.shields.io/badge/RAG%20Pipelines-4B5563" />
      <img src="https://img.shields.io/badge/ChromaDB-FF6446" />
    </td>
  </tr>

  <!-- OBSERVABILITY & TESTING -->
  <tr>
    <td><strong>Observability & Testing</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white" />
      <img src="https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white" />
      <img src="https://img.shields.io/badge/pytest-0A9EDC?logo=pytest&logoColor=white" />
      <img src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white" />
    </td>
  </tr>

</table>

---

## 🔗 Connect

<img src="https://komarev.com/ghpvc/?username=RadwanJama01&style=for-the-badge&color=6AA6FF&label=profile+views" />
