# Hi there, I'm Omar Ahmed 👋

I'm a Computer Engineering student enrolled in a dual-degree program at **Ain Shams University** and the **University of East London**, focusing on **Artificial Intelligence** and **Cybersecurity Engineering**. 

I specialize in building secure AI systems, LLM red-teaming harnesses, machine learning anomaly detection, and low-level firmware.

---

### 🛠️ Tech Stack & Tools

- **Languages:** Python, C++, C, C#, TypeScript, JavaScript, SQL
- **AI & Security:** Prompt Injection & Jailbreak Defense, OWASP LLM Top 10, MITRE ATLAS, scikit-learn, OpenSSL
- **Cloud & DevOps:** AWS (Lambda, CloudWatch, S3), Terraform, GitHub Actions, Linux/POSIX
- **Embedded & Systems:** ARM Cortex-M4 (TM4C123G), OpenOCD, CMake, Ninja, GCC Toolchains
- **Frameworks & Databases:** Next.js, ASP.NET Core, Pydantic, PostgreSQL, SQLite

---

### 🚀 Featured Projects

#### 🧪 [LLM Security Evaluation Harness](https://github.com/)
*An asynchronous automated benchmark and red-teaming harness for evaluating LLM vulnerability resilience.*
- **Threat Vector Coverage:** Evaluates prompt injection, delimiter escapes, indirect context tampering, system prompt/canary leakage, multi-turn roleplay overrides, and SSRF tool parameter injection mapped directly to **OWASP LLM Top 10** and **MITRE ATLAS**.
- **Defense Testing Modes:** Features comparative benchmarking across `baseline`, `prompt_only`, `wrapper_only`, and `hardened` architectures to quantify safety resilience gaps.
- **Robust Evaluation Engine:** Built an async evaluator with token bucket rate limiting (TPM management), semantic refusal filtering, base64/zero-width payload decoding, and tool-call URL allowlist enforcement.
- **Rigorous Statistical Scoring:** Computes resilience scores with **95% Wilson confidence intervals**, tracks false refusal rates via benign control payloads, and outputs structured JSON and Markdown diagnostic reports.

#### 🛡️ [ML-Driven SIEM Agent](https://github.com/)
*Security Information and Event Management agent featuring anomaly detection.*
- Ingests and parses system authentication and access logs in real time.
- Uses **Isolation Forest (scikit-learn)** for unsupervised anomaly and intrusion detection.
- Emits structured alerts with severity scoring to isolate potential threat vectors.

#### 🔒 [P2P Encrypted File Sharing System](https://github.com/)
*A high-performance peer-to-peer file transfer engine in C++.*
- Implemented secure socket communication with **TLS 1.3** via OpenSSL.
- Added cryptographic file integrity validation using **SHA-256** checksum verification.
- Designed clean multi-threaded network handling for reliable decentralized peer transfers.

#### ☁️ [Automated AWS Cloud Threat Response](https://github.com/)
*Infrastructure-as-Code automated defense pipeline.*
- Provisioned complete event-driven security architecture using **Terraform**.
- Uses **AWS Lambda** to automatically remediate non-compliant security groups and suspicious IAM modifications upon CloudWatch alert triggers.


#### 🔍 [File Integrity Monitor](https://github.com/)
*Real-time cryptographic filesystem auditing tool.*
- Continuously monitors critical directory trees and file metadata.
- Employs SHA-256 hashing to detect unauthorized tampering, modifications, or deletions instantly.

#### 🔑 [Password Hygiene & Breach Validator](https://github.com/)
*Python utility evaluating credential strength and exposure.*
- Implements strict entropy rules alongside k-Anonymity checks against the **Have I Been Pwned** API.

#### 📚 [Data Structures: Scapegoat Tree](https://github.com/)
*Modern C++ self-balancing binary search tree.*
- Implemented Scapegoat tree balancing algorithms achieving amortized $O(\log n)$ lookup and modification without storing per-node balance factors.

---

### 🌐 Currently Exploring & Building
- Expanding LLM evaluation harnesses for multi-agent tool execution security.
- Building full-stack media tracking platforms with **Next.js**, **ASP.NET Core**, and **PostgreSQL**.
- Deepening research into software performance evaluation and kernel security.

---

### 📬 Connect With Me

- **LinkedIn:** [linkedin.com/in/omar-ahmed-cybsec007](https://www.linkedin.com/in/omar-ahmed-cybsec007)
- **Email:** omar.ahmed.nes6@gmail.com
