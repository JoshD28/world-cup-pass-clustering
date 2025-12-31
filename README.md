# Soccer Pass Clustering

This repository focused on **clustering soccer passing patterns** using **event-level data**. The objective is to identify and interpret common pass locations and spatial structures through unsupervised learning methods.

##Goals
1. **Preprocess and extract pass event data** from a soccer match dataset.
2. **Apply clustering techniques** to group passes based on their spatial characteristics.
3. **Visualize clustered pass patterns** on a soccer pitch.
4. **Interpret clusters** to describe common passing behaviors and spatial tendencies.

## Data
- **Source:** Soccer event-level data
- **Observations:** Individual pass events
- **Key variables:**  
  - Pass start location (x, y)  
  - Pass end location (x, y)  
  - Additional contextual variables (as available)

## Methods
- **Learning approach:** Unsupervised clustering
- **Clustering techniques:**  
  - Distance-based clustering methods (e.g., k-means or similar, as implemented in the notebook)
- **Preprocessing:**  
  - Feature selection  
  - Coordinate normalization / scaling  
- **Visualization:**  
  - Clustered pass locations plotted on a soccer pitch

## Outputs
- Cluster assignments for pass events
- Pitch visualizations showing spatial pass clusters
- Interpretation of passing patterns associated with each cluster

## How to Run
1. Clone or download this repository.
2. Open the notebook:
   - `Soccer_Pass_Clustering.ipynb`
3. Run all cells sequentially to reproduce the analysis.

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- mplsoccer
- scikit-learn

## Notes
**Unsupervised clustering** was used to explore spatial passing structure.  
Clusters represent **similar pass locations or patterns**, not pass quality or effectiveness.
