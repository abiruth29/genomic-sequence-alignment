# Gene Sequence Alignment and Clustering

This project provides tools for aligning gene sequences using global and local alignment algorithms and clustering them based on their alignment scores. It is designed for bioinformatics research and analysis, particularly in comparing genetic similarity between different organisms.

---

## **Overview**

Gene sequence alignment and clustering are critical in bioinformatics to identify similarities and evolutionary relationships among genes. This project includes the following key features:

1. **Global Sequence Alignment (Needleman-Wunsch Algorithm):**  
   Suitable for aligning entire sequences to determine their overall similarity.

2. **Local Sequence Alignment (Smith-Waterman Algorithm):**  
   Focuses on finding the most similar subsequences within two sequences.

3. **K-means Clustering for Gene Analysis:**  
   Clusters genes into distinct groups based on alignment score similarity.

This tool is highly flexible, allowing researchers to analyze custom sequences and adjust scoring parameters to suit specific needs.

---

## **Features**

### **1. Sequence Alignment**
#### Needleman-Wunsch Algorithm:
- Global alignment designed for full sequence comparison.
- Configurable scoring for matches, mismatches, and gaps.
- Outputs aligned sequences and alignment scores.

#### Smith-Waterman Algorithm:
- Local alignment for detecting the most similar regions within sequences.
- Particularly useful for identifying homologous regions in divergent sequences.
- Outputs aligned subsequences, local scores, and the region of similarity.

### **2. Gene Clustering**
- Computes alignment scores for all gene pairs in the dataset.
- Standardizes scores to ensure compatibility with clustering algorithms.
- Applies K-means clustering to group genes based on similarity.
- Supports visualization of clusters and elbow plots for optimal cluster determination.

---
