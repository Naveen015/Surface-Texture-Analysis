# Surface-Texture-Analysis-Master's Thesis   
## Abstract   
Surface texture image identification from machining surfaces using image processing techniques has become a popular study topic in recent decades. The goal of this work is to use machine learning approaches to recognise diverse machined surface texture photographs. Images of machined components are captured using a camera from mobile device. Two approaches were used. First was to use a Convolutional Neural Network on the surface images to classify the machining process. In second approach, seven statistical characteristics are extracted from collected photos and a feature vector is created. To derive statistical information from machined metal surface pictures, the Grey Level Co-occurrence Matrix is employed. To describe machined surfaces, four machine learning methods were used: Random Forest, Support Vector Machine, Artificial Neural Network, and J48. It is found that the convolutional approach is not learning properly. Artificial Neural Networks and Random Forests have been proven to have 100\% training accuracy and 99 percent cross validation accuracy. The collected results illustrate the effectiveness of the GLCM technique, which may be used to recognise texture pictures.

## Machining Processes
Cutting parameters, tool geometry, work-piece material, chatter, and cutting fluids all contribute to surface roughness. Of these factors, three important parameters are chosen for each machining process. Three levels of values for each parameter were taken. By varying the combination of parameters and levels, 27 configurations of sets of parameters are obtained for each process. In this experiment, six processes were studied which we will see below. Hardened Steel was used for the machining processes.

### Lapping
| Parameters                   |         Levels        |
|                              |   1   |   2   |   3   |
| Lapping Normal Pressure (kg) |  5.0  |  10.0 |  15.0 |
| Abrasive Size (micrometer)   |  1.0  |  3.0  |  5.0  |
| Abrasive Concentration(wt.\%)|  0.5  |  1.0  |  2.0  |


### Grinding
| Parameters                   |         Levels        |
|                              |   1   |   2   |   3   |
| Lapping Normal Pressure (kg) |  5.0  |  10.0 |  15.0 |
| Abrasive Size (micrometer)   |  1.0  |  3.0  |  5.0  |
| Abrasive Concentration(wt.\%)|  0.5  |  1.0  |  2.0  |
