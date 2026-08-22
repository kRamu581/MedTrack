<a id="readme-top"></a>

<!-- PROJECT SHIELDS -->
<div align="center">
  
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![Top ECSOC 2026](https://img.shields.io/badge/Top_ECSOC_2026-FFD700?style=for-the-badge&logoColor=black)](#)

</div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/kRamu81/MedTrack_Application">
    <img src="public/medtrack-logo.svg" alt="MedTrack Logo" width="340">
  </a>

  <h3 align="center">Risk-Adaptive Zero-Trust Security Architecture</h3>
  <p align="center">
    <strong>A Security Posture and Clinical-State-Aware Approach to Hospital Equipment Management</strong>
    <br />
    <a href="https://github.com/kRamu81/MedTrack_Application"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://discord.gg/F7TUpgPzJ">Join Discord</a>
    ·
    <a href="https://github.com/kRamu81/MedTrack_Application/issues">Report Bug</a>
    ·
    <a href="https://github.com/kRamu81/MedTrack_Application/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#what-makes-this-unique">What Makes This Unique? (Explained Simply)</a></li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage & Test Accounts</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

MedTrack is a **Full-Stack Medical Equipment Management Platform** built for hospitals. While standard systems only track when equipment needs repairs, MedTrack is designed from the ground up as an advanced **Zero-Trust Cybersecurity** research project. 

The system acts as a shield, ensuring that external equipment suppliers or compromised technician accounts cannot hack into sensitive clinical networks.

### What Makes This Unique? (Explained Simply)

Imagine a hospital where a smart MRI machine gets a computer virus. A normal security system would instantly disconnect the MRI machine from the network to protect the hospital. **But what if that machine is actively being used to keep a patient alive?**

This project solves that exact problem. It introduces two unique concepts that even a 1st-year student can understand:

1. **The "Risk-Action Matrix":** Instead of just checking if a user has the right password, the system checks *how risky* the medical device currently is (e.g., does it have an outdated software patch?). If the risk is too high, the system automatically blocks access, even if the password is correct!
2. **The "Biomedical Safety Lock":** The system always checks the physical state of the medical device. If the device is marked as IN_USE (attached to a patient) or EMERGENCY, the security system will **never** automatically disconnect it. Instead, it places a "Safety Lock" and demands a human doctor and an IT Admin to both insert a password to override it. 

**In simple terms:** We built a security system that is smart enough to know that saving a patient's life is more important than fighting a computer virus.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* [![React][React.js]][React-url]
* [![Tailwind][Tailwind.css]][Tailwind-url]
* [![Spring][Spring.io]][Spring-url]
* [![Java][Java.com]][Java-url]
* [![OPA](https://img.shields.io/badge/Open%20Policy%20Agent-000000?style=for-the-badge&logo=open-policy-agent&logoColor=white)](#)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

* Java 17 or higher
* Node.js (v16+)
* Maven
* MySQL 8

### Installation

1. Clone the repo
   `sh
   git clone https://github.com/kRamu81/MedTrack_Application.git
   `
2. **Start the Backend**
   `sh
   cd Backend
   mvn spring-boot:run
   `
   * **API URL**: http://localhost:8081

3. **Start the Frontend**
   `sh
   # Open a new terminal in the root directory
   npm install
   npm start
   `
   * **App URL**: http://localhost:3000/MedTrack_Application

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage & Test Accounts

Use the following default accounts to test the Zero-Trust dashboards:

| Role | Email | Password |
|------|-------|----------|
| Hospital Admin | hospital@medtrack.com | dmin123 |
| Technician | 	ech@medtrack.com | 	ech123 |
| Supplier | supplier@medtrack.com | supply123 |

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

Please see our [CONTRIBUTING.md](CONTRIBUTING.md) file for full details on how to get started, assign yourself an issue, and submit a Pull Request.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

##  Top Contributors

A huge thank you to everyone who has contributed to **MedTrack Application**! Your contributions help make this project better every day. 💙

<a href="https://github.com/kRamu81/MedTrack_Application/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=kRamu81/MedTrack_Application&max=500&columns=12" alt="Contributors" />
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the MIT License. See LICENSE for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Project Link: [https://github.com/kRamu81/MedTrack_Application](https://github.com/kRamu81/MedTrack_Application)

💬 **Join our Discord Community:** [https://discord.gg/F7TUpgPzJ](https://discord.gg/F7TUpgPzJ)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/kRamu81/MedTrack_Application.svg?style=for-the-badge
[contributors-url]: https://github.com/kRamu81/MedTrack_Application/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/kRamu81/MedTrack_Application.svg?style=for-the-badge
[forks-url]: https://github.com/kRamu81/MedTrack_Application/network/members
[stars-shield]: https://img.shields.io/github/stars/kRamu81/MedTrack_Application.svg?style=for-the-badge
[stars-url]: https://github.com/kRamu81/MedTrack_Application/stargazers
[issues-shield]: https://img.shields.io/github/issues/kRamu81/MedTrack_Application.svg?style=for-the-badge
[issues-url]: https://github.com/kRamu81/MedTrack_Application/issues
[license-shield]: https://img.shields.io/github/license/kRamu81/MedTrack_Application.svg?style=for-the-badge
[license-url]: https://github.com/kRamu81/MedTrack_Application/blob/master/LICENSE
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Tailwind.css]: https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white
[Tailwind-url]: https://tailwindcss.com/
[Spring.io]: https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white
[Spring-url]: https://spring.io/projects/spring-boot
[Java.com]: https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white
[Java-url]: https://java.com/
# MedTrack
