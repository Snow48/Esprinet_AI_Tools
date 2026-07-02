# Esprinet AI Tools 🚀

Welcome to the repository for **Esprinet Spain** local Artificial Intelligence tools. This space is designed to host practical applications built to run 100% locally on user devices, unlocking the full potential of next-generation **Copilot+ PCs** powered by **Intel® Core™ Ultra** processors.

Our goal is to showcase real-world enterprise use cases where moving AI workloads to the edge delivers immediate, tangible business advantages:

*   **🔒 Absolute Data Privacy:** Process sensitive corporate information, customer emails, or proprietary media entirely on-device, fulfilling strict governance and compliance standards without exposing data to third-party cloud services.
*   **⚡ Ultra-Low Latency:** Eliminate the wait times associated with cloud API round-trips. Local hardware acceleration ensures near-instantaneous inference and processing speeds.
*   **🌐 Network Independence:** Run advanced AI models seamlessly anywhere—whether in high-security offline environments, remote locations, or during network disruptions.
*   **💰 Zero Subscription Costs:** Eradicate recurring monthly cloud fees, token consumption costs, and infrastructure scaling overheads by fully utilizing the hardware assets you already own.

---

## 💻 General System Requirements
To ensure optimal performance and seamless execution of the included local AI models, the following environment is recommended:

* **Operating System:** Windows 11 Pro (Fully optimized for corporate and enterprise ecosystems).
* **Hardware:** Copilot+ PC powered by Intel® Core™ Ultra processors (fully utilizing the integrated NPU). 
    * *Note:* These tools have been successfully tested and benchmarked on an **Intel® Core™ Ultra 7 268V** processor.
* **Software:** Python 3.12 or higher is highly recommended (installed locally).
* **Approach:** 100% local execution (Edge AI) with zero cloud infrastructure costs, ensuring absolute data privacy and security.

---

## 📦 Available Tools

### 1. OpenVINO™ People Counter & Photo Analyzer
This tool leverages the **Intel® OpenVINO™** toolkit to perform ultra-efficient image-based person detection and counting, offloading the heavy workload directly to your local hardware architecture.

* **Corporate Use Case:** Smart workspace optimization, retail foot-traffic analysis, and visual auditing for corporate events.
* **Key Features:**
    * High-speed inference using optimized Computer Vision models.
    * Immediate local processing with real-time bounding box rendering and total headcounts.
* **How to Get Started:**
    1. Navigate to the tool's directory or locate its compressed package (`.zip`) in this repository.
    2. Download the ZIP file to your local machine.
    3. Unzip the file into a local folder on your computer.
    4. Open the extracted folder and read the included `README.md` or installation guide for detailed step-by-step instructions.

---

### 2. Mail Analyzer Tool
A secure, local solution designed for the intelligent analysis, reading, and automation of email workflows using open-source Large Language Models (LLMs) kept entirely within the company's network.

* **Corporate Use Case:** Automated B2B lead classification, incoming customer email sentiment analysis, and structured data extraction without sending confidential data outside the organization.
* **Key Features:**
    * Private text processing adhering strictly to corporate data governance and compliance policies.
    * Seamless integration with local email clients and custom automated workflows.
* **How to Get Started:**
    1. Navigate to the `02_mail_analyzer/` directory.
    2. Install the necessary libraries by executing the dependency installer.
    3. Configure your local parameters and run the main script: `python main.py`.

---

## 🤝 Testing, Support, and Corporate Feedback

This repository is a living initiative designed to provide our partners with practical tools to test, evaluate, and showcase the breakthrough capabilities of **Copilot+ PCs**. Powered by **Intel® Core™ Ultra** processors and running seamlessly under the **Windows 11 Pro** ecosystem, these solutions demonstrate the true efficiency of local NPU and hardware-accelerated Edge AI.

### 💡 We Need Your Feedback!
As you deploy and test these tools with your clients, your hands-on experience is incredibly valuable to us. We actively encourage you to share your insights:
* **Encountered an Issue?** If you run into any bugs, compatibility blocks, or performance hiccups under Windows 11 Pro, please let us know.
* **Have an Idea?** If you think of a new feature, a new local AI use case, or optimization ideas for Intel hardware, we want to hear it.

To share your feedback, report problems, or if you require custom adaptations for end-customer corporate projects, please **open an Issue** here on GitHub or reach out directly to your Esprinet Business Development team.
