## Research Paper Information

**Title:**  
A Two-Stage Hybrid Preprocessing Framework for Quantum Neural Networks in DDoS Intrusion Detection

**Authors:**  
Aadarsh S Nair

**Abstract (Brief):**  
This paper addresses a critical challenge in Quantum Neural Networks (QNNs) applied to cybersecurity: the strong dependency of quantum rotation-based feature encoding on data distribution and scaling. Improperly scaled inputs can lead to degraded quantum gate behavior, unstable optimization, and reduced classification accuracy. To overcome this limitation, we propose a **Two-Stage Hybrid Preprocessing Framework** tailored specifically for quantum learning pipelines. The framework integrates RobustScaler to mitigate the impact of outliers, a logarithmic transformation to correct feature skewness, and StandardScaler for final normalization compatible with quantum rotational encodings. In addition, a hybrid feature selection strategy combining Mutual Information ranking with Random Forest-based refinement is employed to retain only the most quantum-informative features. The proposed approach is extensively evaluated on the CIC-DDoS2019 dataset across multiple experimental scenarios, including binary and multiclass balanced binary classification, balanced and highly imbalanced settings, cross-dataset transfer learning, and single-feature QNN analysis. Experimental results demonstrate consistent performance improvements over conventional preprocessing techniques, highlighting the necessity of tailored preprocessing for unlocking the full potential of QNNs in real-world DDoS intrusion detection.

**Status:**  
Under publication

**Note:**  
The complete manuscript, experimental code, and curated dataset subsets will be made publicly available upon publication.
