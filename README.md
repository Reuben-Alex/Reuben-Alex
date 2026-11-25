<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img src="assets/banner-light.svg" alt="Reuben Alex. AI/ML engineer. I build AI agents that run inside real enterprise systems." width="100%">
</picture>

<p align="center">
  <a href="https://www.linkedin.com/in/reuben-alex-3968b62a2/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:reubenalexa@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-reubenalexa%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://www.credly.com/badges/50b48f39-d11d-4cdf-a907-ebb38c4df6eb"><img alt="Google Cloud Professional ML Engineer" src="https://img.shields.io/badge/Google_Cloud-Professional_ML_Engineer-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white"></a>
</p>

I'm an AI/ML engineer at **[66degrees](https://66degrees.com)** (a Google Cloud AI Partner of the
Year) in Bengaluru. I work forward-deployed with enterprise clients, taking agents built on
**Google ADK, Vertex AI and Gemini** from discovery to production rollout. Across six client
engagements, the part I care about most is the one demos skip: **proving the agent did the right
thing**.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stats-dark.svg">
  <img src="assets/stats-light.svg" alt="80% faster IT ticket closure. About $600K saved on leases. 45% lower handle time for 1,000+ support agents. 3rd of 245 in the Arize track of the Google Cloud Rapid Agent Hackathon." width="100%">
</picture>

## 🧪 Things I've built

Each one makes an agent **show its work**: through traces, a working exploit, a nurse's override,
or judges who never saw the code.

<table>
<tr>
<td width="50%" valign="top">
<a href="https://www.youtube.com/watch?v=hKs4fqzKKHw"><img src="https://img.youtube.com/vi/hKs4fqzKKHw/hqdefault.jpg" alt="ClinTrace demo video" width="100%"></a>

### [ClinTrace](https://github.com/Reuben-Alex/ClinTrace)
🏆 **3rd of 245** · Arize track, Google Cloud Rapid Agent Hackathon

An emergency-department triage agent, built solo. Free-text nursing intake goes in. An ESI level,
red-flag alerts and a routing order come out. Every step is traced in Arize Phoenix, and nurse
overrides recalibrate similar future cases **without retraining**. Validated on real CDC ED data.

`Google ADK` `Vertex AI Agent Engine` `Gemini` `Arize Phoenix` `BigQuery`

[Code](https://github.com/Reuben-Alex/ClinTrace) · [Demo video](https://www.youtube.com/watch?v=hKs4fqzKKHw)
</td>
<td width="50%" valign="top">
<a href="https://www.youtube.com/watch?v=LTIwdPee_do"><img src="https://img.youtube.com/vi/LTIwdPee_do/hqdefault.jpg" alt="Re-entry demo video" width="100%"></a>

### [Re-entry](https://github.com/Reuben-Alex/re-entry)
🔐 **Prove the bug. Prove the fix.**

An agent that writes a fresh exploit for a smart contract, runs it in a local sandbox, and feeds
the real revert reason into its next attempt. It reports a bug only once the exploit has worked,
then patches the contract and replays the exploit to confirm the fix. Agent-written exploits
succeeded on **5 of 13** targets, all **13 of 13** safe controls came back clean, and the misses
are published.

`NVIDIA Nemotron` `Nebius` `Anvil` `Solidity` `Python`

[Code](https://github.com/Reuben-Alex/re-entry) · [Demo video](https://www.youtube.com/watch?v=LTIwdPee_do)
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/Reuben-Alex/tough-crowd"><img src="https://raw.githubusercontent.com/Reuben-Alex/tough-crowd/main/docs/assets/demo.gif" alt="A 15-second product film directed by a coding agent" width="100%"></a>

### [Tough Crowd](https://github.com/Reuben-Alex/tough-crowd)
🎬 **Claude Code plugin**

The agent directs a product film shot by shot. Then three blind judges, who have never seen the
code, the conversation or each other, decide what gets reshot. Zero runtime dependencies. The
benchmark is in progress and reported honestly, including when it doesn't win.

`Claude Code` `HyperFrames` `Node 22` `LLM-as-judge`

[Code](https://github.com/Reuben-Alex/tough-crowd)
</td>
<td width="50%" valign="top">
<a href="https://github.com/Reuben-Alex/Revenant"><img src="https://raw.githubusercontent.com/Reuben-Alex/Revenant/main/docs/img/rising.jpg" alt="Revenant: a burn scar rising on the graveyard map" width="100%"></a>

### [Revenant](https://github.com/Reuben-Alex/Revenant)
🔥 **What burned last summer is not always dead.**

An early-warning map for "zombie" wildfires: fires that smoulder under the snow and flare up on
last year's burn scar. It tests each spring against a chance baseline it has to beat, and says so
when it doesn't.

`NASA FIRMS` `VIIRS` `React` `Python` `Kiro`

[Code](https://github.com/Reuben-Alex/Revenant)
</td>
</tr>
</table>

## 🔭 Currently building

**`adk-upgrade-check`** is an open-source upgrade checker for Google ADK. Run it before you bump
`google-adk` and it flags the code, config and session-database changes the new release will
break, then auto-fixes the safe ones. ADK has shipped breaking changes in five minor releases since
2.0, and nothing checks user code for them yet. *Repo coming soon.*

## 🧰 Toolbox

<p>
  <img alt="Google ADK" src="https://img.shields.io/badge/Google_ADK-4285F4?style=flat-square&logo=google&logoColor=white">
  <img alt="Vertex AI" src="https://img.shields.io/badge/Vertex_AI-4285F4?style=flat-square&logo=googlecloud&logoColor=white">
  <img alt="Gemini" src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white">
  <img alt="Gemini Enterprise" src="https://img.shields.io/badge/Gemini_Enterprise-8E75B2?style=flat-square&logo=googlegemini&logoColor=white">
  <img alt="Dialogflow CX" src="https://img.shields.io/badge/Dialogflow_CX-FF9800?style=flat-square&logo=dialogflow&logoColor=white">
  <img alt="Cloud Run" src="https://img.shields.io/badge/Cloud_Run-4285F4?style=flat-square&logo=googlecloud&logoColor=white">
  <img alt="BigQuery" src="https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white">
  <img alt="Arize Phoenix" src="https://img.shields.io/badge/Arize_Phoenix-evals_%26_tracing-111827?style=flat-square">
  <img alt="OpenTelemetry" src="https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white">
  <img alt="LangChain" src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white">
  <img alt="SQL" src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
  <img alt="Terraform" src="https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white">
</p>

## 🎖️ Certifications

Click a badge to verify it on Credly.

<p>
  <a href="https://www.credly.com/badges/50b48f39-d11d-4cdf-a907-ebb38c4df6eb" title="Professional Machine Learning Engineer · Google Cloud"><img src="https://images.credly.com/size/110x110/images/05e71e7e-92a1-4821-8530-4176b2e3c4b4/image.png" width="96" alt="Google Cloud Professional Machine Learning Engineer"></a>
  <a href="https://www.credly.com/badges/9524e71a-3eb0-45bb-94fe-4d5b0f2380b4" title="Generative AI Leader · Google Cloud"><img src="https://images.credly.com/size/110x110/images/ec23e41a-0f32-4a98-9c00-28925621b281/blob" width="96" alt="Google Cloud Generative AI Leader"></a>
  <a href="https://www.credly.com/badges/f758dcfc-3962-4990-86f0-9a2ee2c824e4" title="Gemini Enterprise Forward Deployed Engineer · Google Cloud"><img src="https://images.credly.com/size/110x110/images/6cd4257b-08f6-4d82-9f62-150796775d9e/blob" width="96" alt="Gemini Enterprise Forward Deployed Engineer"></a>
  <a href="https://www.credly.com/badges/02bf0a72-3575-4f49-b827-c6b5f0ae9dd5" title="Build and Deploy ML Solutions on Vertex AI · Skill Badge"><img src="https://images.credly.com/size/110x110/images/f4c342c9-af98-4352-b54a-a8a166ee8f68/image.png" width="96" alt="Build and Deploy Machine Learning Solutions on Vertex AI skill badge"></a>
  <a href="https://www.credly.com/badges/cc7166d0-9670-416f-afd6-da14b866afab" title="Orchestrate LLM solutions with LangChain · Skill Badge"><img src="https://images.credly.com/size/110x110/images/008980dd-0667-46df-85e1-4f8e2d2c9428/image.png" width="96" alt="Orchestrate PaLM LLM solutions with LangChain skill badge"></a>
  <a href="https://www.credly.com/badges/f49b0324-9120-409e-b141-feab9e06df38" title="Prepare Data for ML APIs on Google Cloud · Skill Badge"><img src="https://images.credly.com/size/110x110/images/68756311-9319-4eeb-a2b7-76defc8dd8a2/image.png" width="96" alt="Prepare Data for ML APIs on Google Cloud skill badge"></a>
  <a href="https://www.credly.com/badges/f424625b-9bf5-4829-a920-0c316d03c6ad" title="Text Prompt Engineering Techniques · Skill Badge"><img src="https://images.credly.com/size/110x110/images/50f95389-785b-48aa-b16b-ebab1bcce020/image.png" width="96" alt="Text Prompt Engineering Techniques skill badge"></a>
</p>

Also: Certified Partner Specialist in Gemini Enterprise Agent Development and in Gemini Enterprise
Deployment (Google Cloud Partner).

<details>
<summary><b>📈 More from the field</b></summary>
<br>

| When | Where | What |
|---|---|---|
| 2025 to now | **66degrees**, Associate AI/ML Engineer | Multi-agent IT and HR assistant (ServiceNow + SAP SuccessFactors) that cut **80%** of manual ticket-closure time. Lease-intelligence agent on Gemini Enterprise covering **800+** leases and saving about **$600K**. Contact-centre intelligence in Genesys, with handle time down **45%** across **1,000+** agents. Dialogflow CX voice bot for a healthcare client covering **30+** call intents. |
| 2024 to 2025 | **66degrees**, AI/ML intern | Computer-vision pipeline on Meta's **SAM2** that segments antennas, RRUs, cabling and mounts from tower imagery, improving tower space utilisation by **30%**. |
| 2023 to 2024 | **Mu Sigma**, internship trainee | Business and IT analysis for analytics engagements. |

</details>

---

<p align="center">
  <sub>Building agents, evals and the unglamorous tooling around them.
  The quickest way to reach me is <a href="https://www.linkedin.com/in/reuben-alex-3968b62a2/">LinkedIn</a>.</sub>
</p>
