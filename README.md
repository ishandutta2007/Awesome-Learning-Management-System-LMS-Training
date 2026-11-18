# Awesome-Learning-Management-System-LMS-Training

# Awesome-Learning-Management-System-LMS-Training

# Awesome Learning Management System (LMS) & Training

> A curated list of top Learning Management System (LMS) and Training platforms — both SaaS/Hosted commercial solutions and open-source alternatives for delivering courses, tracking learner progress, and managing corporate training.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [TalentLMS](#talentlms)
  - [Docebo](#docebo)
  - [Absorb LMS](#absorb-lms)
  - [LearnUpon](#learnupon)
  - [360Learning](#360learning)
  - [Cornerstone OnDemand](#cornerstone-ondemand)
  - [SAP Litmos](#sap-litmos)
- [Open-Source Software](#-open-source-software)
  - [Moodle](#moodle)
  - [Open edX](#open-edx)
  - [Canvas LMS](#canvas-lms)
  - [Chamilo](#chamilo)
  - [ILIAS](#ilias)
  - [Frappe LMS](#frappe-lms)
  - [TutorLoom](#tutorloom)
  - [Euron Open LMS](#euron-open-lms)
  - [Scholiq (Nextcloud)](#scholiq-nextcloud)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted LMS and Training platforms. These are not open-source but are included as reference points for feature comparison.

### TalentLMS
**Type:** SMB-focused cloud LMS
TalentLMS provides course creation, assessments, learning paths, and reporting with a focus on ease of use for small and mid-sized businesses. It offers a free tier for up to 5 users, with paid plans scaling by user count and feature depth.

### Docebo
**Type:** Enterprise AI-powered LMS
Docebo provides a comprehensive enterprise LMS with AI-driven content creation, personalized learning paths, and social learning features. It is positioned for large organizations needing scalability and integrations with HR and CRM systems.

### Absorb LMS
**Type:** Corporate training LMS
Absorb provides a modern LMS with strong reporting, e-commerce capabilities, and integrations with Salesforce and other business tools. It is positioned for mid-market to enterprise organizations delivering external training or customer education.

### LearnUpon
**Type:** LMS for customer and partner training
LearnUpon focuses on external training use cases, with multi-portal support for different audiences (customers, partners, employees) and strong e-commerce capabilities. It is positioned for organizations monetizing training or delivering partner enablement.

### 360Learning
**Type:** Collaborative learning platform
360Learning emphasizes user-generated content and collaborative learning, with tools for subject-matter experts to create courses quickly. It is positioned for organizations wanting to leverage internal expertise rather than top-down course development.

### Cornerstone OnDemand
**Type:** Enterprise talent management with LMS
Cornerstone provides an LMS integrated with broader talent management capabilities including performance, recruiting, and succession planning. It is positioned for large enterprises wanting a unified HCM and learning platform.

### SAP Litmos
**Type:** Corporate LMS within SAP ecosystem
SAP Litmos provides a cloud LMS with course delivery, assessments, and reporting, integrated with the broader SAP ecosystem. It is positioned for organizations already using SAP SuccessFactors or other SAP products.

---

## 🟩 Open-Source Software

Self-hosted, community-driven LMS and Training tools. The open-source ecosystem spans **mature enterprise platforms**, **MOOC-scale systems**, **lighter alternatives**, and **framework-specific solutions**.

### Moodle
**Stack:** PHP / MySQL/PostgreSQL | **License:** GPL-3.0
Moodle is the most widely deployed open-source LMS in the world, used by schools, universities, and corporations in over **240 countries** [citation:2]. It handles the full spectrum of learning needs: courses, **40+ quiz question types**, assignments with rubrics, forums, wikis, SCORM 1.2/2004 packages, competency frameworks, badges, and granular role-based permissions [citation:2]. Its plugin ecosystem includes **2,000+ extensions** covering plagiarism detection, virtual labs, and more. A mobile app is available, and Docker deployment is straightforward via Bitnami images [citation:2]. **Trade-offs:** The admin interface is complex with hundreds of settings; the default theme feels dated; and it is resource-heavy (4+ GB RAM recommended for concurrent users) [citation:2].  
**Best for:** Educational institutions, corporate training departments, and anyone needing a feature-complete, proven LMS with the largest plugin ecosystem.

### Open edX
**Stack:** Python / Django | **License:** AGPL-3.0
Open edX is the platform behind edX.org, built by MIT and Harvard, and is purpose-built for **massive open online courses (MOOCs)** [citation:2]. It excels at video-based learning paths, discussion forums, **auto-graded programming exercises** via XBlocks, certificate generation, and analytics dashboards. Deployment is managed via the **Tutor CLI**, which orchestrates a complex multi-container stack [citation:2]. **Trade-offs:** Resource-heavy (8+ GB RAM recommended for production); complex microservices architecture; steeper learning curve for course creators; and overkill for small teams [citation:2].  
**Best for:** Universities with large enrollments, organizations delivering self-paced training at MOOC scale, and teams needing auto-graded coding exercises.

### Canvas LMS
**Stack:** Ruby on Rails | **License:** AGPL-3.0
Canvas LMS is a full-featured open-source LMS with a **modern interface** and a clean assignment workflow that students and instructors actually like [citation:2]. It handles course creation, enrollment, assessments, gradebook, content delivery, and user roles, with a plugin ecosystem for extending functionality [citation:12]. Canvas Cloud costs $5,000–50,000+ per year for institutional licenses, making self-hosting a significant cost saver [citation:2].  
**Best for:** Educational institutions and training organizations prioritizing user experience and modern UI over the broadest possible feature set.

### Chamilo
**Stack:** PHP / MariaDB/MySQL | **License:** GPL-3.0
Chamilo is a lighter LMS that prioritizes **usability over feature breadth**, with a cleaner admin interface than Moodle and a smaller resource footprint (2 GB RAM is workable) [citation:2]. It supports quizzes, assignments, learning paths, **SCORM packages**, and social learning features (student profiles, messaging). Video conferencing is integrated via BigBlueButton [citation:2]. Deployment is available via Railway with a pre-configured template that runs the installer automatically [citation:15]. **Trade-offs:** Smaller plugin ecosystem and community than Moodle; SCORM support is less robust [citation:2].  
**Best for:** Small schools, training companies, and teams that want an LMS without Moodle's complexity.

### ILIAS
**Stack:** PHP / MySQL | **License:** GPL-3.0
ILIAS is a German-engineered LMS with particularly strong **assessment and competency tracking** features, widely used in corporate compliance training and government education in Europe [citation:2]. It supports SCORM 2004, IMS-QTI import/export, online exams, question pools, and detailed learning progress control [citation:13]. The repository-based architecture allows content to function as an open knowledge platform, not just locked courses [citation:13].  
**Best for:** Organizations delivering compliance training and requiring detailed competency tracking, particularly in European markets.

### Frappe LMS
**Stack:** Python / Frappe Framework / Vue | **License:** GPL-3.0
Frappe LMS is a **100% open-source** LMS built on the Frappe framework (the same ecosystem as ERPNext) [citation:7]. It provides a structured environment for creating and delivering curricula organized into courses, chapters, and lessons, with role-based access control. Its metadata-driven architecture defines entities and schemas through JSON, enabling runtime customization [citation:7]. **Note:** Specific SCORM/xAPI support is not confirmed in available documentation [citation:7].  
**Best for:** Organizations already in the Frappe/ERPNext ecosystem wanting an LMS integrated with their broader business applications.

### TutorLoom
**Stack:** Django / React / PostgreSQL / Redis / Celery | **License:** Apache-2.0
TutorLoom is a **self-hosted, multi-tenant LMS** designed for training institutes and teams, with a course builder, trainer and student portals, and progress tracking [citation:4]. It includes a **Flutter mobile app** for students, with configuration via environment variables and Celery for background tasks. The API includes Swagger/ReDoc documentation [citation:4].  
**Best for:** Training institutes and teams wanting a modern, multi-tenant LMS with a mobile app, accepting the Django/React stack requirements.

### Euron Open LMS
**Stack:** TypeScript / Node.js / React Native | **License:** Open Source
Euron Open LMS provides a full learning platform with a **native mobile app for iOS and Android** (React Native), including offline encrypted video downloads, quizzes, assignments, certificates, and in-app payments (Razorpay on Android, Stripe via web return on iOS) [citation:9]. The architecture is API-first, with the server controlling access, prices, and video licenses. The mobile app supports TOTP two-factor authentication, push notifications, and deep links [citation:9].  
**Best for:** Organizations wanting a modern LMS with a native mobile app and offline video support, accepting the TypeScript/React Native stack.

### Scholiq (Nextcloud)
**Stack:** PHP / Vue / Nextcloud / PostgreSQL | **License:** Open Source
Scholiq is a compliance-training and LMS app for **Nextcloud**, with lifecycle-gated publishing (draft → published → archived), cmi5/xAPI/SCORM content runtime, enrolment with due-date reminders, **Open Badges 3.0 certification** with public verification, and a **compliance-audit wedge** covering NIS2, AVG, and BIO regulations [citation:8]. It includes an EU AI Act gate that requires explicit DPO acknowledgement before enabling AI features [citation:8].  
**Best for:** Organizations already running Nextcloud that need compliance-focused training with certification and audit capabilities.

---

## 📊 Comparison at a Glance

| Software | License | Stack | SCORM/xAPI | Mobile App | Self-Hosted | Best For |
|----------|---------|-------|------------|------------|-------------|----------|
| **Moodle** | GPL-3.0 | PHP/MySQL | ✅ SCORM 1.2/2004 | ✅ Moodle App | ✅ | Full-featured enterprise LMS |
| **Open edX** | AGPL-3.0 | Python/Django | ✅ xAPI via XBlocks | ❌ | ✅ | MOOCs + auto-graded coding |
| **Canvas LMS** | AGPL-3.0 | Ruby/Rails | ✅ | (Check) | ✅ | Modern UI + assignments |
| **Chamilo** | GPL-3.0 | PHP/MariaDB | ✅ (less robust) | ❌ | ✅ | Lighter Moodle alternative |
| **ILIAS** | GPL-3.0 | PHP/MySQL | ✅ SCORM 2004 | ❌ | ✅ | Compliance + competency tracking |
| **Frappe LMS** | GPL-3.0 | Python/Frappe | (Not confirmed) | ❌ | ✅ | ERPNext ecosystem |
| **TutorLoom** | Apache-2.0 | Django/React | ❌ | ✅ Flutter | ✅ | Multi-tenant training institutes |
| **Euron Open LMS** | Open Source | TS/React Native | ✅ | ✅ Native | ✅ | Mobile + offline video |
| **Scholiq** | Open Source | PHP/Nextcloud | ✅ cmi5/xAPI/SCORM | (PWA) | ✅ (Nextcloud) | Compliance + audit |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source LMS or Training tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source.

**Note on the open-source ecosystem:** The open-source LMS landscape is **led decisively by Moodle** for breadth, adoption, and plugin ecosystem (2,000+ extensions, 240+ countries, SCORM/LTI compliance) [citation:2]. **Open edX** is the strongest choice for MOOC-scale delivery and auto-graded coding exercises [citation:2]. **Canvas LMS** offers the best modern UI/UX [citation:2], while **Chamilo** provides a lighter alternative for small teams [citation:2] and **ILIAS** excels at compliance and competency tracking [citation:2]. For organizations in specific ecosystems, **Frappe LMS** integrates with ERPNext [citation:7], **TutorLoom** offers multi-tenant training institutes a Django/React stack [citation:4], **Euron Open LMS** provides a native mobile app with offline video [citation:9], and **Scholiq** brings compliance-focused LMS to Nextcloud [citation:8]. No single open-source project fully replicates the managed simplicity of TalentLMS or the AI depth of Docebo, but these tools cover the core course delivery, assessment, and tracking workflows comprehensively for self-hosted deployments.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
