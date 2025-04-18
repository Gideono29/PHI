# Public Health Disease Surveillance and Architecture Development Project
This involves five different steps

Part 1: Virtual Machine Configuration/Testing

Part 2: Installation, Configuration, and Security of OpenEMR 

Part 3: Generation of Synthea Patient and Syndromic Surveillance Data for Hospital EHRs to Simulate Disease Outbreak

Part 4: Installation and Configuration of Hapi-FHIR Server

Part 5: Interoperability- FHIR Data Exchange with HAPI-FHIR



Part 1: Virtual Machine Configuration and Testing 

A configured virtual machine (VM) environment that simulates a healthcare network infrastructure. This involves configuring a virtual operating system for the following entities:

Aspirus Hospital

Portage Health Hospital

Baraga County Memorial Hospital (BCMH)

Marquette General Hospital (MGH)

Upper Peninsula Health Information Exchange (UPHIE)

Each virtual machine will act as a standalone system representing one of the healthcare organizations. This environment enables safe testing of network architectures and system developments, helping to identify and resolve issues before implementation in live or cloud-based systems.

![](https://github.com/Gideono29/PHI/blob/8add8ec8ff4edaf039cef3dd80f24f47dfa149fb/step1_screenshot%20of%20VMs.png)
![step1_screenshot](https://github.com/Gideono29/PHI/blob/43285950fcfff7be8eb7659a64b1656236d95e02/step1_screenshot.png)


Step 2: Setting up and securing OpenEMR


![train_test_accuracy.png](https://github.com/Gideono29/PHI/blob/36c6012c97788052c89815750f7815a7ba0e477c/Aspirus.png)
![train_test_accuracy.png](https://github.com/Gideono29/PHI/blob/18e4efd9a7fa74bc9c7d132efe0ed592c812fca7/Baraga.png)


Part 3: Generation of Synthea Patient and Syndromic Surveillance Data for Hospital EHRs to Simulate Disease Outbreak

The step involves using Synthea, an open-source tool, to generate synthetic patient data for simulating a disease outbreak, such as COVID-19, across a geographic region. This data helps model and analyze public health scenarios without violating real patient privacy.

Understand synthea

Set up the installation environment

Generate basic Patient data

Generate COVID-19-specific data

Simulate a disease outbreak in a Geographic region

Analyze the output

![](https://github.com/Gideono29/PHI/blob/2bba0894671907083dd8f79343c87100b54a7d03/Aspirus_json.png)

![](https://github.com/Gideono29/PHI/blob/2bba0894671907083dd8f79343c87100b54a7d03/Baraga_json.png)

![](https://github.com/Gideono29/PHI/blob/2bba0894671907083dd8f79343c87100b54a7d03/Marquette_json.png)

![](https://github.com/Gideono29/PHI/blob/2bba0894671907083dd8f79343c87100b54a7d03/Portage_json.png)

Part 4: Installation and Configuration of Hapi-FHIR Server

In public health, HAPI-FHIR supports early disease outbreak detection, rapid data sharing, and coordinated responses, helping to identify trends and shape evidence-based policies for better community health outcomes

-Check if the Docker Daemon is running

-Start and stop Docker Daemon

-List Containers

-List Docker Container Images 

-HAPI FHIR Installation

-Fetch the Latest HAPI FHIR Image

-Configuration via the overridden application.yaml file

-Deploy Docker Container

-open HAPI FHIR portal (http://localhost:8090/

