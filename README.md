
# Molecular Docking Study: SARS-CoV-2 Main Protease (6LU7) with Nirmatrelvir  
## Note  
🚧 **Work in Progress** 🚧  
This project is currently under development. I am practicing molecular docking using tutorials and resources with tools like AutoDock Vina and PyMOL, and the work is not yet complete. Please check back for updates as I make progress!

---

## Overview  
This project involves the molecular docking analysis of the SARS-CoV-2 main protease (PDB ID: 6LU7) with the antiviral drug **Nirmatrelvir**. The main protease (Mpro) plays a critical role in the replication and transcription of SARS-CoV-2, making it an essential target for antiviral drug development. Nirmatrelvir, a key component of the COVID-19 oral therapeutic Paxlovid, has shown high efficacy in inhibiting Mpro.

The goal of this project is to visualize and evaluate the binding interactions between 6LU7 and Nirmatrelvir, providing insights into the structural basis of its inhibition.

---

## Features  
- **Protein Preparation**: Preprocessing of the 6LU7 structure using tools like PyMOL and AutoDockTools.  
- **Ligand Preparation**: Optimization of Nirmatrelvir's structure for docking.  
- **Docking Simulation**: Using AutoDock Vina or similar tools to predict binding poses and scores.  
- **Analysis**: Evaluation of binding interactions, including hydrogen bonds, hydrophobic interactions, and docking scores.


---

## Prerequisites  
- **Software Tools**:  
  - PyMOL  
  - AutoDockTools  
  - AutoDock Vina  
  - Chimera (optional for visualization)  

- **Python Libraries** (if scripts are used):  
  - numpy  
  - biopython  
  - matplotlib  

---

## Usage  
1. **Prepare the Protein**:  
   - Download the 6LU7 PDB structure from the Protein Data Bank.  
   - Remove water molecules, add hydrogens, and prepare the protein for docking.  

2. **Prepare the Ligand**:  
   - Obtain the structure of Nirmatrelvir in `.pdb` format.  
   - Optimize and convert the ligand to `.pdbqt` format.  

3. **Perform Docking**:  
   - Run AutoDock Vina using the prepared files:  
     ```bash
     vina --receptor 6lu7.pdbqt --ligand nirmatrelvir.pdbqt --out docking_results.pdbqt --log docking.log
     ```

4. **Analyze Results**:  
   - Visualize the docking results and analyze binding interactions using PyMOL or Chimera.  
   - Check the docking log for binding affinity scores.


---

## Contributing  
Contributions are welcome! Please submit a pull request or open an issue for any suggestions or improvements.  

---

## License  
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.  

---

## Acknowledgments  
- Protein Data Bank (PDB) for providing the 6LU7 structure.  
- AutoDock and PyMOL developers for their invaluable tools.  
- Researchers working on COVID-19 therapeutic development.
