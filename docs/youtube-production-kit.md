# Cloud2BR YouTube Production Kit

Atlanta, USA

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR - Cloud to be Ready](https://github.com/Cloud2BR)

Last updated: 2026-09-03

----------

Use this production kit for every Cloud2BR video. It turns existing TEC Hub
curriculum and Microsoft Learning Hub repositories into consistent, upload-ready
episodes. Do not publish an episode until its brief and upload checklist are
complete.

## Episode record

Create one record per video before recording. The record is the source of truth
for the video, playlist, description, links, and related GitHub work.

| Field | Required content |
| --- | --- |
| Working ID | Series abbreviation and sequence, for example `RAG-101-01`. |
| Playlist | One language-specific playlist and one technical series. |
| Language | English or Spanish. Do not mix languages in a playlist. |
| Audience | Beginner, intermediate, advanced, or solution architect. |
| Format | Explained, lab, MVP, certification review, demo, or technical talk. |
| Learning outcome | One observable outcome beginning with "By the end, the viewer can...". |
| Source repository | Direct GitHub URL, branch or release used, and relevant folder or document. |
| Business problem | The real-world problem the episode addresses. |
| Prerequisites | Required accounts, subscriptions, tools, knowledge, permissions, and estimated cost. |
| Architecture | Services, data flow, identity path, network assumptions, and diagram source. |
| Validation | Exact success criteria, test data, expected result, and cleanup action. |
| Safety notes | Security, privacy, licensing, production-readiness, and cost caveats. |
| Follow-up | One previous episode, one next episode, and one practical lab or MVP. |

## Upload metadata

Complete every field below at upload time. Keep titles, descriptions, chapters,
thumbnail copy, cards, and end screens consistent with the episode record.

| Asset | Required standard |
| --- | --- |
| Title | Put the searchable technology or outcome first. Keep it specific, accurate, and ideally under 70 characters. Example: `RAG 101: Why LLMs Need Retrieval`. |
| Description opening | First two lines: viewer outcome plus direct GitHub link. These lines must make sense before the "more" expansion. |
| Description body | Include audience, prerequisites, architecture summary, demo scope, validation result, cost and security notes, and related resources. |
| Source link | Link the exact GitHub repository, relevant folder or release, and official Microsoft documentation where appropriate. |
| Chapters | Add timestamped chapters after final edit. Use descriptive, searchable chapter names. |
| Thumbnail | One topic, high contrast, 2-4 words maximum, no tiny code or paragraph text. Use a consistent Cloud2BR visual system. |
| Playlist | Add the technical series and the language playlist. Put the episode in the correct sequence. |
| Audience setting | Set accurately for the intended audience and review made-for-kids status before publishing. |
| Captions | Upload reviewed captions in the spoken language. Add translated captions when an equivalent language episode is not yet available. |
| Cards | Link the most relevant prior concept and a related lab, playlist, or MVP. |
| End screen | Include the next episode, full playlist, and the subscribed channel element. |
| Tags and hashtags | Use relevant technology, learning level, Cloud2BR, and series terms. Avoid unrelated trending tags. |
| Visibility | Upload as private or unlisted for review first; publish only after the review checklist passes. |

### Description template

```text
[One sentence stating the viewer outcome.]
GitHub: [exact repository or folder URL]

In this Cloud2BR [series] episode, you will learn [topic] and see [demonstrated outcome].

Audience: [level]
Prerequisites: [tools, access, knowledge, estimated cost]

What you will learn:
- [outcome 1]
- [outcome 2]
- [outcome 3]

Architecture and implementation:
[services, identity, data, and deployment summary]

Validation:
[what was tested and the expected result]

Security and cost:
[key assumptions, data handling, cleanup, and production caveat]

Related Cloud2BR resources:
- Previous: [URL]
- Next: [URL]
- Lab or MVP: [URL]

Chapters:
00:00 [Opening]
00:00 [Chapter names after final edit]

#Cloud2BR #[technology] #[series]
```

### Title and thumbnail patterns

| Format | Title pattern | Thumbnail copy |
| --- | --- | --- |
| Explained | `What Is [Technology]? [Practical outcome]` | `WHAT IS [TECH]?` |
| Academy | `[Track] [Level]: [Concept or skill]` | `[TRACK] [LEVEL]` |
| Lab | `Build [Outcome] with [Technology]` | `BUILD [OUTCOME]` |
| MVP | `[Outcome]: End-to-End [Technology] MVP` | `[OUTCOME] MVP` |
| Certification | `[Exam]: [Objective] Explained` | `[EXAM] [OBJECTIVE]` |
| Technical talk | `[Technology] Architecture: [Decision or trade-off]` | `[TECH] ARCHITECTURE` |

## Recording and editing skeleton

### Explained episode

1. State the problem and who experiences it.
2. Define the concept in plain language.
3. Explain why it matters and when it should or should not be used.
4. Show the underlying flow or architecture.
5. Connect it to the Microsoft implementation.
6. Link the source repository and the next practical step.

### Lab episode

1. State what is being built and the expected test result.
2. Show the architecture, prerequisites, permissions, and cost boundary.
3. Implement the smallest working version.
4. Run the validation scenario live.
5. Troubleshoot one likely failure mode.
6. Clean up resources and point to the GitHub implementation.

### MVP episode

1. Present the business problem and success criteria.
2. Define requirements, constraints, and non-goals.
3. Walk through architecture and technology choices.
4. Build the core flow.
5. Explain identity, security, data, and cost decisions.
6. Demonstrate the completed scenario and validation results.
7. Show the repository, roadmap, and next enhancement.

## Review gates

### Before recording

- Confirm the source repository is current, public, and linked.
- Test the demo from a clean setup or document every prerequisite.
- Decide whether the content is demonstration-only or production-oriented.
- Prepare sanitized sample data; never record credentials, tokens, customer data, or sensitive browser content.
- Capture the architecture diagram, test result, and cleanup steps.

### Before upload

- Review audio, screen readability, cursor movement, and code zoom level.
- Confirm title, description, chapters, thumbnail, captions, cards, end screen, playlists, and all URLs.
- Verify every GitHub, documentation, and resource link in a signed-out browser.
- State limitations and costs accurately; do not imply Microsoft endorsement or production support.
- Review for secrets, personally identifiable information, internal URLs, and account identifiers.

### After publishing

- Verify public playback, captions, chapters, cards, end screen, and description links.
- Add the video URL to the associated repository README when applicable.
- Review click-through rate, retention, comments, and linked-repository traffic after 7 and 28 days.
- Use results to improve the next episode title, thumbnail, pacing, and topic sequence.

## Source-to-series backlog

Each row below is a video-planning skeleton. A repository may create several
episodes; start with an explainer, lab, or MVP based on the recommended format.
Operational and profile repositories are marked support-only rather than treated
as a video topic.

### Cloud2BR TEC Hub

| Source | Series | First episode skeleton | Format |
| --- | --- | --- | --- |
| [ML 101](https://github.com/Cloud2BR-TEC/ai-academy-101-ml) | Cloud2BR Academy | `ML 101: What Is Machine Learning?` Cover data, features, labels, training, evaluation, and one practical use case. | Explained |
| [ML 102](https://github.com/Cloud2BR-TEC/ai-academy-102-ml) | Cloud2BR Academy | `ML 102: Build, Train, and Deploy a Model` Demonstrate the full development loop and validation. | Lab |
| [ML 103](https://github.com/Cloud2BR-TEC/ai-academy-103-ml) | Cloud2BR Academy | `ML 103: Taking Machine Learning to Production` Cover lifecycle, monitoring, automation, and operating ownership. | Technical talk |
| [RAG 101](https://github.com/Cloud2BR-TEC/ai-academy-101-rag) | RAG Academy | `RAG 101: Why LLMs Need Retrieval` Explain limitations, embeddings, vector search, chunking, and augmentation. | Explained |
| [RAG 102](https://github.com/Cloud2BR-TEC/ai-academy-102-rag) | RAG Academy | `RAG 102: Build an End-to-End RAG Chatbot` Build ingestion, indexing, retrieval, prompts, and chat UI. | Lab |
| [RAG 103](https://github.com/Cloud2BR-TEC/ai-academy-103-rag) | RAG Academy | `RAG 103: Production RAG Architecture` Cover evaluation, security, monitoring, scalability, and cost. | Technical talk |
| [AI Operations](https://github.com/Cloud2BR-TEC/ai-academy-101-ops) | AI Operations | `What Is GenAIOps?` Compare GenAIOps and MLOps across evaluation, deployment, monitoring, governance, and improvement. | Explained |
| [Document ETL](https://github.com/Cloud2BR-TEC/ai-academy-101-docs-etl) | Document Intelligence | `Document Processing: From PDF to Structured Data` Compare the supported extraction approaches. | Explained |
| [Cloudy Video Library](https://github.com/Cloud2BR-TEC/cloudy-overview-videos) | Channel operations | Curate existing content into playlists, create cards and end screens, and identify gaps for new episodes. | Curation |
| [TEC Hub](https://github.com/Cloud2BR-TEC/tec-hub) | Channel operations | `How to Learn with Cloud2BR Academy` Show the Foundations to Practice to Apply to Grow pathway. | Channel overview |
| [Organization Admin Center](https://github.com/Cloud2BR-TEC/org-admin-center) | Support-only | Do not make a public episode by default; use for organization operations only. | Support-only |

### Microsoft Learning Hub: AI, agents, and MCP

| Source | Series | First episode skeleton | Format |
| --- | --- | --- | --- |
| [Azure MCP Blueprint](https://github.com/Cloud2BR-MSFTLearningHub/Azure-MCP-blueprint) | MCP on Azure | `What Is MCP?` Explain clients, servers, tools, authentication, and Azure hosting options before the first build. | Explained |
| [AI Agent Infrastructure](https://github.com/Cloud2BR-MSFTLearningHub/AI-Agent-Infra-Blueprint) | AI Agents | `Build the Foundation for an Azure AI Agent` Explain infrastructure, identity, network assumptions, and deployment. | Lab |
| [Azure Arc Recommendations Agent](https://github.com/Cloud2BR-MSFTLearningHub/AzureArcRecommendations-AI-Agent) | AI Agents | `Build an Azure Recommendations Agent` Demonstrate a focused agent workflow and validation scenario. | MVP |
| [Agentic AI Media Assistant](https://github.com/Cloud2BR-MSFTLearningHub/Agentic-AI-Media-Assistant) | AI Agents | `Build a Multimodal AI Media Assistant` Walk through inputs, tools, safety, and outputs. | MVP |
| [AI Shopping Assistant](https://github.com/Cloud2BR-MSFTLearningHub/Agentic-DevOps-AI-Shopping) | AI Agents | `Build a Multi-Agent AI Shopping Assistant` Cover multimodal design, agent roles, orchestration, and testing. | MVP |
| [Fabric MCP Agent2Agent](https://github.com/Cloud2BR-MSFTLearningHub/Fabric-MCP-Agent2Agent) | AI Agents | `Agent-to-Agent Data Workflows with Fabric and Copilot Studio` Demonstrate the integration path. | Lab |
| [Agent 365](https://github.com/Cloud2BR-MSFTLearningHub/Agent365-Overview) | AI Agents | `What Is Agent 365?` Establish the service context, capabilities, and adoption considerations. | Explained |
| [RAG ChatBot](https://github.com/Cloud2BR-MSFTLearningHub/RAG-ChatBot-Implementation) | RAG Academy | `RAG Chatbot: From Prototype to Zero Trust` Compare basic and zero-trust architecture choices. | MVP |
| [Azure Text Embeddings](https://github.com/Cloud2BR-MSFTLearningHub/Azure-Text-Embedding-Overview) | RAG Academy | `Embeddings on Azure: Quality, Latency, and Cost` Show selection and performance trade-offs. | Lab |
| [Azure ML Overview](https://github.com/Cloud2BR-MSFTLearningHub/Azure-ML-Overview) | Cloud2BR Academy | `Azure Machine Learning: Core Components Explained` Map workspace, data, compute, training, and deployment. | Explained |
| [Azure ML Advanced](https://github.com/Cloud2BR-MSFTLearningHub/Azure-ML-Advanced) | Cloud2BR Academy | `Advanced Azure ML: From Experiment to Managed Delivery` Explore advanced components and decisions. | Technical talk |
| [Azure MLOps](https://github.com/Cloud2BR-MSFTLearningHub/Azure-MLOps-Overview) | AI Operations | `MLOps on Azure: A Practical Lifecycle` Show evaluation, release, monitoring, and rollback. | Lab |
| [GenAIOps Maturity](https://github.com/Cloud2BR-MSFTLearningHub/GenAIOpsMaturityLevels) | AI Operations | `GenAIOps Maturity: From Prototype to Production` Assess capabilities and define next improvements. | Explained |

### Microsoft Learning Hub: Fabric, data, and document intelligence

| Source | Series | First episode skeleton | Format |
| --- | --- | --- | --- |
| [Fabric Enterprise Framework](https://github.com/Cloud2BR-MSFTLearningHub/Fabric-EnterpriseFramework) | Microsoft Fabric | `Fabric Enterprise Architecture` Cover governance, deployment, monitoring, observability, and cost. | Technical talk |
| [Fabric Essentials Workshop](https://github.com/Cloud2BR-MSFTLearningHub/MS-Fabric-Essentials-Workshop) | Microsoft Fabric | `Microsoft Fabric Essentials: Build a Lakehouse Foundation` Demonstrate workspace, lakehouse, Git, and CI/CD concepts. | Lab |
| [Fabric AI Retail](https://github.com/Cloud2BR-MSFTLearningHub/Fabric-AI-Retail-Demo) | Cloud2BR MVPs | `Build a Fabric AI Retail Solution` Present the retail scenario, data flow, and demo. | MVP |
| [Fabric Date Hierarchy](https://github.com/Cloud2BR-MSFTLearningHub/Fabric-Date-Hierarchy-Accelerator) | Microsoft Fabric | `Standardize Date Hierarchies in Fabric and Power BI` Demonstrate reusable model logic. | Lab |
| [Fabric SKU Estimation](https://github.com/Cloud2BR-MSFTLearningHub/Fabric-SKU-EstimationTool) | Microsoft Fabric | `Estimating Fabric Capacity: What the Numbers Mean` Explain estimates, assumptions, and validation boundaries. | Explained |
| [Azure Databases and Purview](https://github.com/Cloud2BR-MSFTLearningHub/Azure-Databases-Purview-Advisor) | Azure Data | `Azure Database Services and Purview: A Practical Overview` Cover setup, modeling, performance, and governance. | Explained |
| [Database Space Optimization](https://github.com/Cloud2BR-MSFTLearningHub/azDataBase-Freeing-Unused-Space) | Azure Data | `Optimize Azure Database Space Safely` Show assessment, validation, and cleanup process. | Lab |
| [MySQL IOPS](https://github.com/Cloud2BR-MSFTLearningHub/MySQL-autoscale-IOPS) | Azure Data | `What Are IOPS? MySQL Autoscaling Explained` Teach performance signals and scaling decisions. | Explained |
| [Synapse Dynamic Remove Blanks](https://github.com/Cloud2BR-MSFTLearningHub/azSynapse-Dynamic-RemoveBlanks) | Azure Data | `Clean Data Dynamically in Azure Synapse` Demonstrate the transformation and test result. | Lab |
| [PDF Layout Processing](https://github.com/Cloud2BR-MSFTLearningHub/PDFs-Layouts-Processing-Fapp-DocIntelligence) | Document Intelligence | `Extract Text, Tables, and Checkboxes from PDFs` Build the extraction and data-storage flow. | Lab |
| [Invoice Processing: Document Intelligence](https://github.com/Cloud2BR-MSFTLearningHub/PDFs-Invoice-Processing-Fapp-DocIntelligence) | Document Intelligence | `Build Intelligent Invoice Processing` Demonstrate storage, extraction, Cosmos DB, validation, and errors. | MVP |
| [Invoice Processing: Open Framework](https://github.com/Cloud2BR-MSFTLearningHub/PDFs-Invoice-Processing-Fapp-OpenFramework) | Document Intelligence | `Open Framework vs. Document Intelligence for Invoices` Compare architecture, extraction results, and trade-offs. | Technical talk |
| [Visual Cue Processing](https://github.com/Cloud2BR-MSFTLearningHub/PDFs-MultiLayout-VisualCue-AzureAI-Document-Processing) | Document Intelligence | `Extract Visual Cues from Complex PDFs` Cover selected values, tables, checkboxes, and quality validation. | Lab |
| [Blob File Summary Tool](https://github.com/Cloud2BR-MSFTLearningHub/BlobFileUpload-SummaryTool) | File to AI Insight | `Build an AI File Summary Pipeline` Demonstrate uploads, events, functions, extraction, and outputs. | MVP |

### Microsoft Learning Hub: security, DevSecOps, and architecture

| Source | Series | First episode skeleton | Format |
| --- | --- | --- | --- |
| [Security Campaign](https://github.com/Cloud2BR-MSFTLearningHub/Security-Campaign) | Microsoft Security | `Microsoft Security: Where to Start` Frame the security learning journey and core services. | Explained |
| [Microsoft Entra](https://github.com/Cloud2BR-MSFTLearningHub/Entra-Overview) | Microsoft Security | `What Is Microsoft Entra?` Explain identity, access, RBAC, and validation. | Explained |
| [Microsoft Intune](https://github.com/Cloud2BR-MSFTLearningHub/Intune-Overview) | Microsoft Security | `Microsoft Intune: Device Management Fundamentals` Cover enrollment, policy, compliance, and test devices. | Lab |
| [Microsoft Purview](https://github.com/Cloud2BR-MSFTLearningHub/Purview-Setup-Overview) | Microsoft Security | `Microsoft Purview: Data Governance Fundamentals` Show data governance scope and setup choices. | Explained |
| [Microsoft Sentinel](https://github.com/Cloud2BR-MSFTLearningHub/Sentinel-Setup-Overview) | Microsoft Security | `Microsoft Sentinel: First Workspace and Query` Demonstrate setup, data, and investigation basics. | Lab |
| [Defender for Cloud](https://github.com/Cloud2BR-MSFTLearningHub/Defender-Setup-Overview) | Microsoft Security | `Defender for Cloud: Setup and Security Posture` Show environment setup and validation. | Lab |
| [Security Copilot](https://github.com/Cloud2BR-MSFTLearningHub/Security-Copilot-Overview) | Microsoft Security | `What Is Security Copilot?` Demonstrate responsible use, prompts, and analyst validation. | Explained |
| [Microsoft 365 E5/E7](https://github.com/Cloud2BR-MSFTLearningHub/M365-E5-E7-Overview) | Microsoft Security | `Microsoft 365 E5 and E7: Capabilities Overview` Explain capability mapping and licensing caveats. | Explained |
| [Azure Artifact Signing](https://github.com/Cloud2BR-MSFTLearningHub/Azure-ArtifactSigning-DevOps) | Cloud2BR DevSecOps | `Build a Secure Artifact Signing Pipeline` Demonstrate OIDC, Key Vault, HSM, Terraform, and GitHub Actions. | MVP |
| [Azure Terraform Templates](https://github.com/Cloud2BR-MSFTLearningHub/AzureTerraformTemplates-v0.0.0) | Cloud2BR DevSecOps | `Infrastructure as Code with Azure Terraform Templates` Build and validate a repeatable deployment. | Lab |
| [GitHub Overview](https://github.com/Cloud2BR-MSFTLearningHub/GitHub-Overview) | Cloud2BR DevSecOps | `GitHub for Cloud Delivery: The Essential Workflow` Explain issues, pull requests, Actions, and release flow. | Explained |
| [Azure App Development](https://github.com/Cloud2BR-MSFTLearningHub/Azure-App-Dev-Overview) | Cloud Architecture | `Azure Application Development Services: Choosing a Starting Point` Compare services and decision criteria. | Explained |
| [Azure Function Temp Usage](https://github.com/Cloud2BR-MSFTLearningHub/AzureFunctionApp-TempUsage) | Cloud Architecture | `Azure Functions Temporary Storage: Behavior and Limits` Demonstrate safe file handling and operational impact. | Lab |
| [Azure Capacity](https://github.com/Cloud2BR-MSFTLearningHub/Azure-Capacity-Overview) | Cloud Architecture | `Azure Capacity Planning Explained` Cover demand, quotas, regions, and validation. | Explained |
| [Architecture Flow Designer](https://github.com/Cloud2BR-MSFTLearningHub/arch-flows-designer) | Cloud Architecture | `Design an Azure Architecture Diagram in the Browser` Build a service flow and explain trade-offs. | Lab |
| [Cloud Evolution](https://github.com/Cloud2BR-MSFTLearningHub/Demystifying-Cloud-Evolution) | Cloud Architecture | `How Cloud Architecture Evolved` Connect evolution, capacity, efficiency, Kubernetes, and Azure design. | Explained |
| [Azure Digital Twins](https://github.com/Cloud2BR-MSFTLearningHub/Azure-DigitalTwins-Overview) | Azure Digital Twins | `What Is Azure Digital Twins?` Model a physical environment and introduce DTDL, telemetry, and relationships. | Explained |
| [SAP and Logic Apps](https://github.com/Cloud2BR-MSFTLearningHub/SAP-integration-AzLogicApps) | Cloud Integration | `SAP Integration with Azure Logic Apps` Demonstrate authentication, cookie, and CSRF handling choices. | Lab |
| [Demos and Tech Talks](https://github.com/Cloud2BR-MSFTLearningHub/DemosScenarios-TechTalks) | Channel operations | Curate reusable scenarios into category playlists and identify demo-to-MVP follow-ups. | Curation |

### Microsoft Learning Hub: certification and support assets

| Source | Series | First episode skeleton | Format |
| --- | --- | --- | --- |
| [AI-900 Study Guide](https://github.com/Cloud2BR-MSFTLearningHub/AI-900StudyGuide) | Certification Academy | `AI-900: Generative AI, NLP, and Computer Vision` Teach objectives with short demonstrations. | Certification review |
| [AI-102 Study Guide](https://github.com/Cloud2BR-MSFTLearningHub/AI-102StudyGuide) | Certification Academy | `AI-102: RAG, Document Intelligence, and AI Search` Connect exam objectives to labs. | Certification review |
| [DP-900 Study Guide](https://github.com/Cloud2BR-MSFTLearningHub/DP-900StudyGuide) | Certification Academy | `DP-900: Data Warehousing, NoSQL, and Analytics` Explain core data concepts and services. | Certification review |
| [DP-100 Study Guide](https://github.com/Cloud2BR-MSFTLearningHub/DP-100StudyGuide) | Certification Academy | `DP-100: Operationalizing Machine Learning` Connect study objectives to ML lifecycle practices. | Certification review |
| [DP-600 Study Guide](https://github.com/Cloud2BR-MSFTLearningHub/DP-600StudyGuide) | Certification Academy | `DP-600: Microsoft Fabric Analytics` Link certification objectives to Fabric labs. | Certification review |
| [AZ-400 Study Guide](https://github.com/Cloud2BR-MSFTLearningHub/AZ-400StudyGuide) | Certification Academy | `AZ-400: DevOps Practices in Action` Explain delivery, security, automation, and measurement. | Certification review |
| [GH-900 Study Guide](https://github.com/Cloud2BR-MSFTLearningHub/GH-900StudyGuide) | Certification Academy | `GH-900: GitHub Foundations` Cover collaboration and platform concepts. | Certification review |
| [GH-300 Study Guide](https://github.com/Cloud2BR-MSFTLearningHub/GH-300StudyGuide) | Certification Academy | `GH-300: GitHub Copilot and AI Delivery` Connect objectives to responsible developer workflows. | Certification review |
| [Organization Catalog](https://github.com/Cloud2BR-MSFTLearningHub/org-catalog) | Channel operations | Use as the central directory linked from descriptions; do not create a standalone technical episode by default. | Support-only |
| [Organization Discussions](https://github.com/Cloud2BR-MSFTLearningHub/org-discussions) | Channel operations | Use for viewer questions, correction requests, and episode feedback; do not create a standalone episode by default. | Support-only |
| [Repository Template](https://github.com/Cloud2BR-MSFTLearningHub/org-repo-template) | Channel operations | Use as the README companion template for video-enabled repositories. | Support-only |

## Launch scheduling skeleton

Plan one production cycle per episode and avoid recording the full backlog before
the first release data is available.

| Week | Deliverable | Exit criteria |
| --- | --- | --- |
| 1 | Select episode and complete its record. | Source, audience, outcome, safety notes, and next step approved. |
| 2 | Script and technical rehearsal. | Demo starts from documented prerequisites and passes validation. |
| 3 | Record and edit. | Screen, audio, captions draft, thumbnail draft, and chapters are ready. |
| 4 | Review and publish. | Metadata, links, playlists, cards, end screen, and public playback pass review. |
| 5 | Measure and improve. | Record CTR, retention, comments, and repository traffic; apply one improvement to the next episode. |

Start with the first 30-video sequence in the [Cloud2BR YouTube strategy](youtube.md).
Keep the remaining rows in this backlog as planned content until their episode
record, demo, and publishing assets are complete.