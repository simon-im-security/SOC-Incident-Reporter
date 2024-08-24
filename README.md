# SOC Incident Reporter

**Version**: 2024.08.24  
**Author**: Simon .I

## Overview

The **SOC Incident Reporter** is a WPF-based tool designed to assist Security Operations Centre (SOC) teams in efficiently recording and managing cybersecurity incidents. The tool provides a guided workflow for analysts through three primary stages:

- **New Incident**: For initial client contact.
- **Continuing Incident**: For ongoing investigations.
- **Closing Incident**: For final resolution and summary.

Each stage includes specific sections for **Internal Use** (e.g., incident type, threat level, initial findings) and **External Use** (e.g., client communication, responses). This structured approach helps ensure comprehensive documentation and consistent client interaction during the incident management process.

## Key Features

- **User-Friendly Interface**: Built with WPF, the tool offers a clean and intuitive interface for SOC teams to navigate through incident stages.
- **Customisable Fields**: Analysts can select predefined options or enter custom information for incident types, threat levels, client responses, and more.
- **Save and Reload Data**: The tool allows users to save their work locally and reload it later, ensuring continuity in managing ongoing incidents.
- **Export to Plain Text**: Upon completion, the tool exports incident details into a plain text file, ready for integration into ITSM platforms like ServiceNow.

## Screenshot

![SOC Incident Reporter Interface](https://github.com/simon-im-security/SOC-Incident-Reporter/blob/main/Images/image_main.png?raw=true)

## Download

You can download the **SOC Incident Reporter** as a ZIP file containing an executable (EXE) from the [release page](https://github.com/simon-im-security/SOC-Incident-Reporter/releases). The source code is available in this project repository.

## Integration with IT Management Systems

The SOC Incident Reporter is particularly helpful for assisting with ServiceNow and other IT management systems that are not specifically designed for cybersecurity. By providing a structured and easy-to-use tool, it ensures that incident management is thorough and streamlined, even within systems that may not have dedicated cybersecurity features.

## Getting Started

1. **Installation**: Download the ZIP file from the [release page](https://github.com/simon-im-security/SOC-Incident-Reporter/releases).
2. **Run the Script**: Extract the ZIP file and execute the EXE to launch the SOC Incident Reporter.
3. **Select Incident Type**: Choose between New, Continuing, or Closing Incident to begin documenting the incident.
4. **Save and Export**: Save your progress at any time and export the final report when the incident is resolved.

## How It Works

The SOC Incident Reporter is structured to handle the different stages of incident management:

- **New Incident**: Capture initial information such as the type of cybersecurity incident, its threat level, and the initial findings. Communicate with the client using predefined responses or custom messages.
- **Continuing Incident**: Document ongoing findings, summarise client contacts, and outline the next steps in the investigation.
- **Closing Incident**: Provide a resolution summary and finalise client communication, ensuring the incident is closed effectively.

---
