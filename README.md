# Public Health Disease Surveillance and Architecture Development Project
This involves five different steps

Step 1: Virtual Machine Configuration/Testing

Step 2: Installation, Configuration, and Security of OpenEMR 

Step 3: Generation of Synthea Patient and Syndromic Surveillance Data for Hospital EHRs to Simulate Disease Outbreak

Step 4: Installation and Configuration of Hapi-FHIR Server

Step 5: Interoperability- FHIR Data Exchange with HAPI-FHIR

Step 1: A configured virtual machine (VM) environment that simulates a healthcare network infrastructure. This involves configuring a virtual operating system for the following entities:

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
Generate COVID-19 specific data
Simulate a disease outbreak in a Geographic region
Analyze the output
