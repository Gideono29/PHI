# Public Health Disease Surveillance and Architecture Development Project
This involves five different steps

Part 1: Virtual Machine Configuration/Testing

Part 2: Installation, Configuration, and Security of OpenEMR 

Part 3: Generation of Synthea Patient and Syndromic Surveillance Data for Hospital EHRs to Simulate Disease Outbreak

Part 4: Installation and Configuration of Hapi-FHIR Server

Part 5: Interoperability- FHIR Data Exchange with HAPI-FHIR

![](https://github.com/Gideono29/PHI/blob/f5d3904928ff7ab27eb048e19f18c9461c7844c4/AD_part_3.pdf)

Part 1: Virtual Machine Configuration and Testing 
-

A configured virtual machine (VM) environment that simulates a healthcare network infrastructure. This involves configuring a virtual operating system for the following hospital
-
- Set up and join VPN
- Connect to the Cluster
- Navigate the Cluster
- Create the VM for the following entities
  -
  - Aspirus
  - Portage Health Hospital
  - Baraga County Memorial Hospital (BCMH)
  - Marguette General Hospital
  - Upper Peninsula Information Exchange (UPHIE)
  
Each virtual machine will act as a standalone system representing one of the healthcare organizations. This environment enables safe testing of network architectures and system developments, helping to identify and resolve issues before implementation in live or cloud-based systems.

![](https://github.com/Gideono29/PHI/blob/8add8ec8ff4edaf039cef3dd80f24f47dfa149fb/step1_screenshot%20of%20VMs.png)
![step1_screenshot](https://github.com/Gideono29/PHI/blob/43285950fcfff7be8eb7659a64b1656236d95e02/step1_screenshot.png)


Step 2: Setting up and securing OpenEMR
-
Install and configure OpenEMR, an open-source electronic health record (EHR) system for the four virtual hospitals. OpenEMR supports patient scheduling, billing, clinical decision support, and a customizable patient portal, making it a flexible and widely used tool for healthcare management.
-

 -Update and upgrade the Ubuntu Server
 - Install necessary packages
 - Create a MySQL database and user for OpenEMR
 - Download and extract OpenEMR
 - Configure Apache
 - Complete OpenEMR installation via the web-based setup
 - Enable automatic security updates
 - Configure a firewall
 - Securing Apache
 - Restart Apache
 - Use strong passwords
 - Configure regular backups
 - Keep OpenEMR up to date
 

![train_test_accuracy.png](https://github.com/Gideono29/PHI/blob/36c6012c97788052c89815750f7815a7ba0e477c/Aspirus.png)
![train_test_accuracy.png](https://github.com/Gideono29/PHI/blob/18e4efd9a7fa74bc9c7d132efe0ed592c812fca7/Baraga.png)


Part 3: Generation of Synthea Patient and Syndromic Surveillance Data for Hospital EHRs to Simulate Disease Outbreak
-

The step involves using Synthea to generate synthetic patient data for simulating a disease outbreak such as COVID-19 across a geographic region. This data helps model and analyze public health scenarios without violating real patient privacy.
-
 - Install Synthea
 - Download the latest version of Synthea from the official GitHub repository.
 - Create a directory for Synthea and move the JAR file
 - Generate disease simulation message
 


![](https://github.com/Gideono29/PHI/blob/2bba0894671907083dd8f79343c87100b54a7d03/Aspirus_json.png)

![](https://github.com/Gideono29/PHI/blob/2bba0894671907083dd8f79343c87100b54a7d03/Baraga_json.png)

![](https://github.com/Gideono29/PHI/blob/2bba0894671907083dd8f79343c87100b54a7d03/Marquette_json.png)

![](https://github.com/Gideono29/PHI/blob/2bba0894671907083dd8f79343c87100b54a7d03/Portage_json.png)

Part 4: Installation and Configuration of Hapi-FHIR Server
-

In public health, HAPI-FHIR supports early disease outbreak detection, rapid data sharing, and coordinated responses, helping to identify trends and shape evidence-based policies for better community health outcomes
-
- Check if the Docker Daemon is running
- Start and stop Docker Daemon
- List Containers
- List Docker Container Images 
- HAPI FHIR Installation
- Fetch the Latest HAPI FHIR Image
- Configuration via the overridden application.yaml file
- Deploy Docker Container
- Open HAPI FHIR portal (http://localhost:8090/
![](https://github.com/Gideono29/PHI/blob/476d1d4725356a57227bb6dd73a661f8f315afe0/default_web_UI.png)

Part 5: Interoperability- FHIR Data Exchange with HAPI-FHIR
-

This section explores how HAPI-FHIR supports the acceptance and processing of HL7 FHIR messages for public health surveillance. HAPI-FHIR enables integration with various EHR systems, allowing public health agencies to retrieve and monitor critical patient data efficiently.
-
- Installing POSTMAN
- Log in to HAPI-FHIR Virtual Machine
- CRUD Operations using HAPI FHIR REST API
- Swagger UI
- Create a New Practitioner
- Search for Practitioner instances
- Search with Conditions
- HAPI FHIR Dashboard
- Python REST API

![](https://github.com/Gideono29/PHI/blob/527b47c4facb9fd2f69524330e826f9a5e31e1f7/response.copy.png)


Part 6: Aggregation and Visualization of Data for Disease Outbreak Surveillance
-  
  - Data Aggregation
  - Data Visualization

