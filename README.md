# ChainChecker  

**Release (Beta)**  

ChainChecker is a lightweight, offline analysis application designed to examine chains of transmission for, primarily, viral hemorrhagic fevers such as Ebola, Marburg, and Nipah. The tool allows epidemiologists and public health practitioners to manage outbreak line lists, visualize chains of transmission, overlay genetic sequencing data, and apply analytical layers to better understand chains of transmission.  

---

## Features & Capabilities  

### 1. **Offline Analysis**  
- Works locally on your computer with no internet dependency or external servers.  

### 2. **Disease-Specific Settings**  
- Currently supports Ebola, Marburg, and Nipah. However, other pathogens could be used but exposure windows and mutation windows might not be applicable. 
- Default incubation and evolutionary rates are pre-set per disease but can be customized.  

### 3. **Multi-Language Support**  
- Available in **English**, **French**, and **Spanish**.  

### 4. **Data Management**  
- Upload outbreak line lists and map variables (e.g., case ID, symptom onset, exposure links).  
- Mandatory fields:  
  - Unique Identifier  
  - Illness Onset Date  
- Optional fields expand functionality (death, isolation, healthcare facilities, epidemiologic classification, relationships, etc.).  
- Edit and export updated line lists directly within the app.  
- Save column configurations to re-use for file updates.

### 5. **Chain of Transmission Visualization**  
- Interactive graph of cases based on illness onset date.  
- Dots represent individuals; connecting lines represent epidemiological links.  
- Legend displays total cases, unlinked cases, and cases with genetic sequencing data.  
- Adjustable date ranges for outbreak visualization.  

### 6. **Graph Options**  
- Customize chain visualization with:  
  - Case detail pop-ups  
  - Icon styles  
  - Gridlines toggle  
  - Transmission chain height  
  - Evolutionary rate  
  - Incubation period  
  - Biological feasibility overlay

### 7. **Hover & Filter Options**  
- Hover-over bubbles configurable to display selected variables.  
- Filter visualization by any mapped variables (e.g., dates, facilities, case attributes).  

### 8. **Data Layers**  
- Enhance visualizations with additional analytical layers, including:  
  - **Healthcare Facility Stays** (admissions/discharges)  
  - **Isolation Dates**  
  - **Relationships** (e.g., family, healthcare worker)  
  - **Color Coding** by chosen variables  
  - **Exposure Windows**  
  - **Suspected Healthcare-Acquired Cases**  
  - **Mutation Windows**  
  - **Biological Feasibility**  
  - **Link Strength Indicators**  

### 9. **Healthcare Facility Visualization**  
- View patient journies through specific healthcare facilities.  
- Switch between facility-level or patient-level visualizations.  
- Overlay data layers for deeper insights.  

### 10. **Data Validation & Anomaly Detection**  
- Detect anomalies in dates (e.g., onset, death, hospitalization).  
- Identify potential **nosocomial transmission events** automatically.  

### 11. **Genetic Sequencing Integration**  
- Upload genetic distance matrices or pairwise genetic distances.  
- Visualize genetic data alongside epidemiologic chains.  
- Identify nucleotide differences between cases.  
- Highlight genetic feasibility of suspected transmission links.  

---

## 📦 Installation & Setup  

1. Download ChainChecker from Releases.  
2. Extract the `.zip` file and run the included **run.bat** file.  

---

## 🛠️ Status  

- **Beta Release** — actively being tested and refined.  
- Future releases may add support for more pathogens and advanced analytics.  

---
