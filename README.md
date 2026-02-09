## How to use this repository

This repository shares the SCAPS simulation files and supporting material used in our JV fitting and analysis.

### Repository structure
- **Typical device fits**: SCAPS files fitted to representative devices (fits based on **mean/average JV metrics**).
- **Champion fits**: SCAPS files fitted to **champion devices**. The **experimental champion JV metrics** used as fitting targets are included in this folder.
- **Figures**: Figures used in the manuscript / supporting material.

### Running the simulations
1. Clone or download the repository.
2. Open the relevant SCAPS file (typical or champion) in **SCAPS 1D**.

3. **Start with the champion-device fits** (`Champion fits`).  
   These fits are anchored to measured experimental JVs and are provided as a practical starting point to develop intuition for *realistic* layer/interface parameter ranges and their influence on the JV response.

4. **Move to the typical-device fits** (`Typical device fits`).  
   Once you have a feel for the parameter space, use the typical-device fits (based on mean/average JV metrics) for **reproducibility**, **interpretation**, and **stack-to-stack comparison**. These files represent the **final fitted results reported in the paper**.

3. **Extend as needed**  
   From either starting point, users can perform parameter variation / sensitivity sweeps within the realistic ranges suggested by the champion fits, and evaluate how changes propagate toward the JV behavior of typical devices.



### More details
A **PDF in the main directory** includes additional simulation results and a discussion addressing referee suggestions and requests for readers who want deeper modeling context.



Arranged by: Mohammad Dehnavi
