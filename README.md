# Hi there, I'm Marco Wüthrich 👋

**Senior Software Engineer | Technical Leader | Kotlin Enthusiast**

🌐 **[marcow.dev](https://marcow.dev)**: my portfolio and CV

I am a dedicated Software Engineer with a passion for building robust, scalable applications. My engineering journey began with Java in 2018, but I quickly transitioned to **Kotlin**, where my true passion lies. Having co-founded and managed startups (serving as Head of Engineering and Partner), I bring a unique blend of deep technical expertise and a solid understanding of the business strategies required to successfully run a software company.

Currently, I am working as a Senior Software Engineer, focusing heavily on Kotlin and Angular. Alongside that, I build and ship my own product: **AirPace**, a breathwork app for iOS and Android written in **Kotlin Multiplatform** from a single shared codebase.

## 🌬️ AirPace: precision breathwork for iOS & Android

**[airpace.io](https://airpace.io)** · launching on the App Store and Google Play

AirPace is a tactile breathing coach: millisecond-accurate pacing with voice, haptic and ambient-sound guidance, so you can practise with your eyes closed. It covers classic techniques (box breathing, 4-7-8, coherent breathing, physiological sigh, pranayama), your own patterns, daily Commitments, and Breath Radar, which reads your heart rhythm from a Bluetooth heart-rate sensor and prompts you when your breathing drifts. I designed, built and run it on my own, from product design to backend.

**How it's built**
* **One codebase, two native apps:** Kotlin Multiplatform with the whole UI in **Compose Multiplatform**, plus thin platform bridges for audio, haptics, Bluetooth LE, the camera, HealthKit and Health Connect.
* **A deterministic engine:** a millisecond-precise session state machine, offline-first persistence in **SQLDelight**, and opt-in cross-device sync to a self-hosted, Swiss-hosted **PocketBase**, merged with conflict rules written for each field.
* **Measured on device:** a camera-PPG resonance scanner and real-time heart-rate variability from BLE sensors, all processed on the phone.
* **Quality as a gate:** about 4,000 host tests, with the Compose UI tests running on the JVM (Robolectric) *and* the iOS simulator; a coverage gate holding the core logic above 95% (98.8% today); Maestro end-to-end flows on Android and iOS, multi-device sync included; Detekt, Android Lint and static security analysis all held at zero findings.
* **Delivery:** trunk-based, on self-hosted CI (a Raspberry Pi 5 and a Mac), 30 Architecture Decision Records, English and German from day one, subscriptions through RevenueCat.
* **An agentic engineering workflow:** research, spec, then implementation, with AI coding agents working in parallel under the same review and test gates as any change.

*The source is private; the product is at [airpace.io](https://airpace.io).*

### 🛠️ Technical Arsenal

* **Languages:** Kotlin, Java, TypeScript
* **Backend:** Spring Framework, Ktor
* **Frontend:** Angular
* **Architecture:** Microservices & Monolithic architectures, KMP (Kotlin Multiplatform)
* **DevOps & Cloud:** Kubernetes, OpenShift, ArgoCD, GitLab CI/CD pipelines

### 🏆 Certifications & Education

I believe in continuous learning and scientifically grounded engineering practices. Here are a few of my key certifications:
* **Development:** Spring Certified Professional (VMware, 2024), Kotlin Developer (Hyperskill, 2024), Angular Certification
* **Architecture & Quality:** iSAQB® Certified Professional for Software Architecture (Foundation), ISTQB® Certified Tester
* **Education:** Bachelor of Science in Computer Science (FFHS) | Dipl. Techniker HF Informatik (OOP)

### 🌿 Also on GitHub: Green-Print

**[green-print](https://github.com/marcowuethrich/green-print)**
An enterprise-grade Kotlin Multiplatform (KMP) & Quarkus spatial inventory system. 
* **Highlights:** Features a unique top-down houseplant blueprint, offline-first SQLDelight caching, and OIDC security. 

---
📫 **Let's Connect:** [marcow.dev](https://marcow.dev) · [LinkedIn](https://www.linkedin.com/in/marco-wuethrich-zh/)
