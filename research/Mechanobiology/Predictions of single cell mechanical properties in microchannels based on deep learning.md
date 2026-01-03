Cellular components determine its mechanical properties. The elastic module is a critical biomarker indicative of various diseases and cellular state transitions. Understanding the cellular mechanics leads to an improvement in cell therapy.

Measurement of the mechanical properties is challenging due to the heterogeneity and size. Multiple techniques using physical and engineering principles has been utilized with limited throughput. A high number of samples is required to make adequate conclusions due to the cell variability and physical changes in prolonged scenarios, generating the need for more efficient measurement methods.

Microfluidics can provide a high throughput method, but lacking in precision due to the complex forces involved. These methods allow classification of multiple sub-populations of cells. The experimental data is obtained using a contactless micro-constriction microfluidics device, obtaining the elastic module by studying snapshots of the cell deformation. The process is denominated real time deformability citometry (RT-DC).

Machine learning methods are used to analyze the large amount of raw data produced by the RT-DC, backed by the extensive use of ML methods in medicine. By applying deep convolutional neural networks connected to a long short-term memory network a classificator for constitutive equations can be made, obtaining promising results.

Cell deformation in various stages is simulated using COMSOL, obtaining a dataset, containing positional, mechanical and temporal data. A multi input CNN is developed (MI-CNN) capable of predicting the Young's module using the adequate constitutive equation.
## Introduction
1. Mechanical properties as biomarkers
2. Speed of measurement
3. Need for high throughput
4. Microfluidics as solution
5. ML to manage high throughput 
6. Aim and scope of paper

## FEA
1. Symmetry
2. Geometry of simulation
3. COMSOL
4. Arbitrary lagrange eulerian equation
5. Navier-Stokes
6. Elastic formulation and deformation
7. Solid Fluid interaction
## Constitutive laws
1. Relevant features
2. Constitutive equations
3. M-R model
4. N-H model
5. Compressibility
## Dataset
1. Dataset generation
2. Snapshots
## ML model
1. Representation of input
2. CNN
3. MI-CNN
## Regression results
1. NN Ensemble
2. Training and validation
3. Metric results
4. Influence of number of snapshots
5. Computational requirements
## Classification results
1. Selecting constitutive equation
2. Preprocessing with noise
3. Influence of cell deformation

# Conclusions

# Pending questions
- The Young's module can be obtained using a single snapshot?
#paper #ML #CNN #MechanoBiology #CellDeformation #NNEnsemble #FEA #FSI #Microfluidic #LSTM