# cyclopus

<div align="center">

<img width="350" height="350" alt="octopus" src="https://github.com/user-attachments/assets/6678a8b5-cafb-4297-a9f0-ec4109d0229c" />


[![GitHub stars](https://img.shields.io/github/stars/Iankulani/cyclopus?style=for-the-badge&logo=github)](https://github.com/Iankulani/cyclopus/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Iankulani/cyclopus?style=for-the-badge&logo=github)](https://github.com/Iankulani/cyclopus/network)
[![GitHub watchers](https://img.shields.io/github/watchers/Iankulani/cyclopus?style=for-the-badge&logo=github)](https://github.com/Iankulani/cyclopus/watchers)
[![GitHub contributors](https://img.shields.io/github/contributors/Iankulani/cyclopus?style=for-the-badge&logo=github)](https://github.com/Iankulani/cyclopus/graphs/contributors)
[![GitHub last commit](https://img.shields.io/github/last-commit/Iankulani/cyclopus?style=for-the-badge&logo=git)](https://github.com/Iankulani/cyclopus/commits/main)
[![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Linux%20%7C%20Windows%20%7C%20macOS-blue?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/Iankulani/cyclopus)
[![Python](https://img.shields.io/badge/python-3.x-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)

</div>

---
Cyclopus is a next-generation, multi-vector cybersecurity command-and-control framework meticulously engineered for large-scale cyber defense drills, red team operations, and adversarial simulation exercises. Unlike conventional penetration testing tools that restrict operators to a single interface or limited communication channels, Cyclopus revolutionizes remote access by enabling security professionals to initiate, manage, and monitor complex attack campaigns through an unprecedented array of everyday messaging platforms. The tool seamlessly integrates with Discord, Telegram, Slack, Google Chat, WhatsApp, and Signal, transforming these ubiquitous communication ecosystems into powerful covert command conduits. This multi-platform architecture ensures that cybersecurity drill coordinators can maintain persistent, anonymous, and resilient operational control from virtually any device, anywhere in the world, without relying on traditional infrastructure that might be flagged or blocked by defensive systems.

---
At the heart of Cyclopus lies a sophisticated Social Engineering Module, purpose-built to simulate the most dangerous human-centric threats facing modern organizations. This module automates the creation and deployment of hyper-personalized phishing campaigns, pretexting scenarios, and business email compromise simulations. It leverages artificial intelligence to craft contextually relevant lures that mimic internal communications, vendor interactions, or executive requests, complete with dynamically generated credential-harvesting pages and malicious attachment delivery systems. 

---
The module includes comprehensive analytics dashboards that track user interaction metrics, including email open rates, link click-through patterns, credential submission behaviors, and multi-factor authentication bypass attempts. Drill coordinators can launch simultaneous social engineering attacks across email, SMS, and messaging platforms, providing a holistic assessment of an organization's human firewall resilience. The module also features automated response handling, allowing operators to engage in real-time conversational pretexting with targets during live cyber drills, testing employee susceptibility to sophisticated impersonation tactics.

---

Complementing the human-centric attack vectors, Cyclopus incorporates a full-spectrum Network Penetration Testing Module that transforms the tool into a comprehensive infrastructure assessment powerhouse. This module includes an extensive arsenal of reconnaissance, scanning, exploitation, and post-exploitation capabilities. It features automated network mapping, advanced port scanning with service fingerprinting, vulnerability identification against extensive CVE databases, and seamless integration with industry-standard exploit frameworks. 

---

The module supports both internal and external network assessments, enabling drill participants to simulate attacker movements from initial foothold to lateral traversal across segmented environments. Advanced features include SMB relay attacks, Active Directory enumeration, Kerberos ticket harvesting, pass-the-hash techniques, and cloud infrastructure probing for AWS, Azure, and Google Cloud environments. The network module operates in tandem with the social engineering component, allowing operators to chain attacks—for instance, using a phishing email to deliver a payload that establishes network persistence, followed by automated internal reconnaissance and privilege escalation.


For comprehensive endpoint visibility and behavioral monitoring, Cyclopus features a powerful Keylogger Deployment Module that enables drill coordinators to deploy both user-mode and kernel-mode keystroke logging capabilities across Windows, macOS, and Linux endpoints. This module goes beyond simple keystroke capture, incorporating advanced features such as clipboard monitoring, screenshot capture at configurable intervals, active window tracking, application usage analytics, and even microphone and webcam activation for complete environmental awareness. 

The keylogger module operates with multiple deployment methods, including memory-only execution that leaves no forensic footprint, file-based persistence for long-term monitoring, and polymorphic variants that evade signature-based detection. During cyber drills, this module provides invaluable insights into user behavior patterns, sensitive data entry points, and application workflow analysis. The captured data is encrypted in real-time and exfiltrated through the platform's command channels, ensuring operational security while providing drill orchestrators with granular visibility into endpoint activities.

Cyclopus distinguishes itself through its advanced Multi-Platform Configuration Engine, which simplifies the complex process of establishing and managing command channels across all supported communication platforms. The tool includes dedicated configuration wizards for each platform, offering granular control over bot creation, API token management, webhook configurations, channel permissions, and encrypted session establishment. For Discord, Cyclopus configures custom bot instances with slash command support and private channel creation. Telegram integration leverages bot API configurations with inline keyboard support and encrypted message handling. 

Slack configuration encompasses workspace app creation, OAuth token management, and channel-specific command routing. Google Chat integration utilizes space webhooks and service account authentications. WhatsApp deployment leverages business API configurations with session persistence. Signal integration utilizes encrypted signaling protocols for maximum confidentiality. All configurations are centrally managed through a unified dashboard, enabling drill coordinators to deploy, test, and switch between platforms instantaneously.

Ultimately, Cyclopus is designed specifically for cyber drill execution, providing drill orchestrators with real-time team collaboration features, comprehensive logging for after-action reporting, automated scoring mechanisms, and scenario-based attack playbooks. Its revolutionary architecture ensures that cybersecurity teams can train against the most sophisticated threats in realistic, multi-channel environments, preparing organizations for the complex, hybrid attacks that characterize today's threat landscape.


# Clone repository

```bash
git clone https://github.com/Iankulani/cyclopus.git
cd cyclopus
```
# Create virtual environment
```bash
python3 -m venv venv
source venv/bin/activate  # Linux/macOS
```
# OR
```bash
venv\Scripts\activate     # Windows
```

# Install development dependencies

```bash
pip install -r requirements.txt
pip install -e .
```
# Alternative: Force pip install as root (NOT recommended!)

```bash
pip install -r requirements.txt --break-system-packages
```
# Run tests
```bash
python3 commands-test.py
```

# How to run the repo
```bash
python3 cyclopus.py
```

# Check code style

```bash
black cyclopus.py
flake8 cyclopus.py
```


# Documentation
[![Documentation](https://img.shields.io/badge/📖-Documentation-0066ff?style=for-the-badge&logo=readthedocs)](https://iankulani.github.io/Cyclopus-Documentation/)

# References

# Star History
```bash
```
