# MRPC_DRD1_2024: Multigap Resistive Plate Chambers Data Analysis and HV Scan

Welcome to the **MRPC_DRD1_2024** repository! This repository serves as a comprehensive tool for **Lab 6.B: MRPC Characterization**, part of the **DRD1 Gaseous Detectors School** at CERN (November 27–December 6, 2024). It includes all the resources required to conduct the session, focusing on the analysis of MRPC data and high voltage (HV) scans.

The [documentation page of the detector](http://nuc1.fis.ucm.es/minitrasgo/) includes instructions on several functions as the HV modification commands, for example.

---

## Repository Structure

### 1. **[MRPC_DRD1_LAB.ipynb](MRPC_DRD1_LAB.ipynb)**
   - **Purpose**: A guided Google Colab notebook designed to streamline the session.
   - **Features**:
     - Step-by-step instructions for analyzing MRPC data.
     - Code snippets for generating histograms and performance plots.
     - Tools for calibrating and characterizing the mini-telescope.

   - **Usage**: Open the notebook in **Google Colab**, and integrate it with Google Drive for seamless access to the `DATA` directory. No downloads or installations are needed on your local machine.

### 2. **DATA/**
   - **Purpose**: Contains the experimental data files in `.txt` format.
   - **Content**: Pre-collected datasets for HV scan, efficiency calculation, and other key metrics.
   - **Usage**: The notebook automatically loads these files for analysis. Ensure the `DATA` directory is synced to your Google Drive.

---

## Session Overview: Lab 6.B - MRPC Characterization

### **Introduction**
The aim of this session is to characterize a **mini-telescope** composed of four MRPC planes. Students will:
- Analyze the telescope’s efficiency, charge spectrum, background rate, streamer probability, and time resolution as a function of HV.
- Perform charge and time calibrations.

No advanced Python skills are required. The session is beginner-friendly and guided through provided notebooks.

---

### **Experimental Setup**
- **Telescope Design**: Four MRPC planes enclosed in sealed gas-tight plastic boxes, with feed-throughs for gas and HV connections.
- **Key Components**:
  - **Electrodes**: Made of 2 mm float glass, separated by nylon mono-filaments.
  - **Readout System**: High-speed electronics encode time and charge with precision better than 30 ps and 100 ns, respectively.
  - **DAQ System**: Uses TRB3sc for time processing, with time precision under 20 ps.
- **Gas**: Operates with pure R134a.
- **HV**: Optimal operation at ~5.4 kV per gap.

---

### **Work Plan**
1. **Introduction** (30 min)
   - Overview of the mini-telescope and software.
   - Setup and control instructions.

2. **Data Acquisition and Analysis** (3 hours)
   - Run HV scans (~30 minutes per voltage point).
   - Generate and analyze histograms (charge, time, position).
   - Study angular distributions.

3. **Final Plots** (30 min)
   - Produce efficiency, charge spectrum, streamer probability, background rate, and time resolution plots.

---

## How to Use This Repository
1. **Google Colab Integration**:
   - Open `MRPC_DRD1_LAB.ipynb` in Google Colab.
   - Mount your Google Drive when prompted.
   - The notebook automatically accesses data from the `DATA` directory.

2. **No Installation Needed**:
   - Everything runs in the cloud.
   - No software or data files need to be downloaded to your local PC.

3. **Deliverables**:
   - Final performance plots.
   - Insight into the operational characteristics of MRPCs.

---

## References
- **Performance of the HADES ToF Wall Front-End Electronics**:  
  [DOI: 10.1109/TNS.2010.2056928](https://doi.org/10.1109/TNS.2010.2056928)

- **TRB3: High Precision TDC Platform**:  
  [DOI: 10.1088/1748-0221/8/12/c12043](https://doi.org/10.1088/1748-0221/8/12/c12043)

---

## About the DRD1 School
The DRD1 Gaseous Detectors School provides hands-on experience with state-of-the-art gaseous detector technologies, including MRPCs. The school targets PhD students and young scientists entering the field.

- **Dates**: November 27–December 6, 2024.
- **Location**: CERN.
- **Format**: Morning lectures and afternoon practical sessions.
- **Registration**: Free for students, but accommodation and travel expenses are self-funded.

For more information, visit the school’s official page.

---

### Contributing
Feel free to fork this repository and contribute improvements! For questions or support during the session, contact the organizers.

Happy analyzing! 🎉
