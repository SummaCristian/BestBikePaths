<div align='center'>
  <img src='./icon.png' width='150'>

# Best Bike Paths
</div>

**Best Bike Paths (BBP)** is an integrated platform that bridges this gap by combining personal ride tracking with collaborative mapping of bike path conditions. The system enables cyclists to record and analyse their trips while actively contributing to a shared repository of information regarding path quality, obstacles, and overall cycling experience.

By leveraging both individual data and collective insights, BBP supports informed route selection and fosters a more transparent and reliable cycling environment.

Through this unified approach, BBP aims to enhance the overall cycling experience, empowering users to navigate urban spaces with greater confidence, safety, and awareness, while promoting a community-oriented model of sustainable mobility.

>[!NOTE]
> This project was developed for the Software Engineering 2 course at Politecnico di Milano.
> It's worth half the exam, corresponding to the `R&DD` project.
> It consists of producing two technical documents, a *Requirements Analysis and Specification Document* (RASD) and a *Design Document* (DD).

<p align="center">
  <table align="center">
    <tr>
      <td align="center">
        <a href="https://github.com/summacristian">
          <img src="https://github.com/summacristian.png" width="70" alt="SummaCristian"/><br>
          <sub><b>SummaCristian</b></sub>
        </a><br>
        <sub>Cristian Summa</sub>
      </td>
      <td align="center">
        <a href="https://github.com/mailp99">
          <img src="https://github.com/mailp99.png" width="70" alt="mailp99"/><br>
          <sub><b>Mailp99</b></sub>
        </a><br>
        <sub>Mathias Rodigari</sub>
      </td>
    </tr>
  </table>
</p>

# RASD
The *Requirements Analysis and Specification Document* (RASD) focuses on defining the problem domain, identifying stakeholders, and formalizing the system requirements for Best Bike Paths.

It describes the platform’s objectives, the needs it aims to address, and the context in which it operates. The document provides a structured analysis of functional and non-functional requirements, outlining what the system must do and the constraints under which it must operate.

In particular, the RASD includes:

- An overview of the system purpose and scope
- Stakeholder and user identification
- Scenarios and use cases describing expected interactions
- Functional requirements detailing the platform’s core features
- Non-functional requirements such as usability, reliability, and performance
- Domain assumptions, dependencies, and constraints

This document serves as the foundation for the design phase, ensuring that all system features are well-defined and aligned with user needs before implementation decisions are made.

<p align="center">
  <a href="./DeliveryFolder/RASDv2.pdf">
    <img src="https://img.shields.io/badge/📘%20Read%20the%20Full%20RASD-PDF-red?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Read the Full RASD">
  </a>
</p>

# DD
The *Design Document* (DD) translates the requirements identified in the RASD into a concrete system architecture.

It describes how the platform is structured and how its components interact to fulfill the specified requirements. The document provides a high-level and detailed view of the system’s organization, focusing on design choices, component responsibilities, and data management strategies.

In particular, the DD includes:
- The overall architectural design and rationale
- Component decomposition and their interactions
- Data design and key entities
- Interface definitions and interaction flows for the iOS version of the client
- Deployment considerations and technological choices
- Testing strategy and plan

Together, the RASD and DD provide a complete conceptual and technical description of Best Bike Paths, guiding development and ensuring consistency between requirements, design, and implementation.

<p align="center">
  <a href="./DeliveryFolder/DDv1.pdf">
    <img src="https://img.shields.io/badge/📘%20Read%20the%20Full%20DD-PDF-red?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Read the Full DD">
  </a>
</p>

## User Interface
A significant part of the *Design Document* focuses on a high-fidelity prototype of the iOS client, used to illustrate user flows and interactions with the system.

These mockups were designed in Figma and are the result of a complete usability study conducted in parallel with the system architecture design. The two activities influenced each other, shaping several key design decisions.

Below are some of these mockups. The full set is available in Chapter 3 of the *Design Document*.

<div align='center'>
  <img src="./DD/Mockups/LoginScreen.PNG" width="250" alt="Login Screen">
  <img src="./DD/Mockups/MainScreen.PNG" width="250" alt="Main Screen">
  <img src="./DD/Mockups/ShowPaths_Map.PNG" width="250" alt="Show Paths Screen">
  <img src="./DD/Mockups/Trip_Navigation2.PNG" width="250" alt="Trip Navigation Screen">
  <img src="./DD/Mockups/AddPath_Manual_Screen.PNG" width="250" alt="Add Path (Manual) Screen">
  <img src="./DD/Mockups/Path_Automatic.png" width="250" alt="Add Path (Automatic) Screen">
</div>