<div align="center">
  <img src="image.png" alt="CyberAasaan Banner" width="100%">
</div>

# CyberAasaan: The Seamless Student Journey 🛡️🎓

**Safer digital experiences for students—simple, explainable, effective.**

CyberAasaan is an edge-native, AI-driven security ecosystem designed specifically for the paradoxical needs of university campuses. It transforms cybersecurity from a punitive barrier into a continuous, personalized learning tool while mathematically proving student privacy. Built as part of the **AMD Slingshot Hackathon** by "The Hackademic Heroes."

---

## 🛑 The Problem

Universities must secure thousands of naive first-year users while preserving an open, privacy-first academic environment. Existing enterprise tools like Cisco Umbrella or Microsoft Defender fail because:
1. They rely on "hard blocks" and confusing IT policies without explaining *why* something was blocked.
2. They ship raw student telemetry (Personally Identifiable Information - PII) to the cloud.

With education being the **#1 most attacked sector globally** (74% of breaches involving the human element), a new approach is necessary.

---

## 💡 Our Solution: CyberAasaan

CyberAasaan flips the script. We push the AI models directly to the edge, training them locally, and only sending anonymized mathematical weights back to the central server. The platform treats cybersecurity as a pedagogical journey across a structured roadmap of **4 active phases + 1 future evolution**.

### Four Unfair Advantages (USP)
1. **Pedagogical Security:** Every blocked threat becomes a personalized teachable moment, not just a dead end.
2. **Mathematical Privacy:** Our ε-differential privacy provides mathematical proof of anonymity—not a fragile legal promise.
3. **Invisible Authentication:** Behavioral biometrics add zero friction to the student's day.
4. **Compliant by Architecture:** FERPA & GDPR compliance is baked into the infrastructure since raw PII physically cannot leave the device.

---

## 🚀 The 4 Active Phases

### Phase 1: "Teach-Back" Phishing Interceptor
A high-impact browser extension. When a student clicks a fake link, a locally trained model intercepts it and uses the **Teach-Back AI** to explain the anatomy of the attack (e.g., manipulated URLs, psychological urgency) in plain English.

### Phase 2: Invisible Security Layer
Replaces annoying 2FA prompts with passive **Behavioral Biometrics** (typing cadence). It operates invisibly to detect account takeovers seamlessly.

### Phase 3: Privacy-Preserving Analytics
A secure data pipeline utilizing **Federated Learning and Differential Privacy**. By pushing local training, educators and IT staff get actionable insights and threat analytics without ever exposing raw PII.

### Phase 4: Explainable Command Center
An XAI-powered dashboard for campus IT. It converts raw network logs into plain-language incident reports and visualizations, eliminating alert fatigue.

### Phase 5 (Future Evolution): Decentralized Identity
An upgrade to utilize **Zero-Knowledge Proofs (ZKP)**. Students can mathematically prove their enrollment or access permissions without revealing their name, age, or major.

---

## 🏗️ Architecture & Technology Stack

CyberAasaan is optimized from edge to cloud, bypassing expensive cloud APIs and maximizing localized compute power.

### Frontend & Student Edge
* **React.js & TailwindCSS:** High-performance browser extension UI.
* **Native Messaging API:** Securely bridges the React extension to the shared local ONNX inference engine.

### AI & Machine Learning
* **ONNX Runtime with DirectML:** Unified inference engine natively targeting edge NPUs/GPUs.
* **DistilBERT (Fine-Tuned):** NPU-accelerated NLP model trained on *PhishTank & OpenPhish* datasets for real-time URL classification.
* **Phi-3-mini LLM:** Provides the intricate on-demand "Teach-Back" explanations.

### Privacy Pipeline
* **Flower (flwr) & Docker:** Containerized Python FL microservice communicating with Node.js via localhost REST.
* **Opacus (Meta):** PyTorch-native library injecting differential privacy noise during client training rounds (ε-differential privacy guarantees). Models are exported to ONNX for inference.

### Backend Infrastructure
* **Supabase (PostgreSQL):** Scalable backend handling telemetry limits (MVP runs via a 500MB free-tier).
* **ELK Stack:** Open-source SIEM backbone for the IT command center (Production).
* **Node.js / Express:** Secure secure API wrapper managing telemetry.

---

## 💻 AMD Hardware Utilization

Our system runs entirely on advanced AMD architecture to ensure massive cost-savings and rigorous privacy. 

* **The Student Edge (AMD Ryzen™ AI NPU):** Runs lightweight, always-on ONNX Runtime inference (DistilBERT classification and biometric modeling) continuously with low power consumption.
* **Zero-Cost Inference (AMD Radeon™ Graphics):** Fast, heavy LLM inference (Phi-3-mini) is performed locally via discrete Radeon graphics, using DirectML to fall back uniformly across integrated iGPUs.
* **The Central Hub (AMD EPYC™ Servers):** Production deployments leverage the massive core counts and bandwidth of EPYC server instances to aggregate thousands of differential privacy weight updates per minute securely.

---

## 💲 Cost Strategy

By keeping ML inference strictly on the student device and running federated networking on open-source stacks, our Lean MVP costs exactly **$0.00** to run (via Supabase Free Tier + Vercel). Production estimates for a 5,000 student campus cap out at a highly affordable ~$80–200/month.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE) - see the LICENSE file for details.

---

<br>
<div align="center">
  <p>Architected for Privacy • Designed for Education<br><br>
  <b>Karthigaiselvam R</b><br>
  <i>Team Leader, The Hackademic Heroes</i></p>
</div>
