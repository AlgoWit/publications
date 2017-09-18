# Geometric SMOTE: Effective oversampling for imbalanced learning through a geometric extension of SMOTE

### Abstract
Learning from imbalanced datasets is a challenging problem for standard classification algorithms. Although different approaches exist to address this problem, the generation of artificial data for the minority class is a more general approach compared to algorithmic modifications. SMOTE algorithm and its variations generate synthetic samples along the line segment that joins minority class samples. In this paper we propose Geometric SMOTE (G-SMOTE) as the geometric generalization of SMOTE data generation mechanism. G-SMOTE generates synthetic samples in a geometric region of the input space, around each selected minority instance. While in the basic configuration this region is a hyper-sphere, G-SMOTE allows its deformation to a hyper-spheroid and finally to a line segment, emulating the SMOTE mechanism. The performance of  G-SMOTE is compared against multiple standard oversampling algorithms. We present empirical results that show a significant improvement in the quality of the generated data when G-SMOTE is used as an oversampling algorithm.

### Paper
*To be updated soon...*

### Experimental procedure
[Preprint](https://github.com/gdouzas/reproducible-research/blob/master/gsmote/preprint/experiment.ipynb)

### Implementation of algorithms
[G-SMOTE](https://github.com/gdouzas/imbalanced-tools/blob/master/imbtools/algorithms/geometric_smote.py)