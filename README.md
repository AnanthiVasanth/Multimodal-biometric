# Multimodal-biometric
#Biometric authentication with forehead and periocular
Steps in multimodal biometric:
1. Locating the eyes with Viola Jones algorithm
2. Segmenting the periocular and forehead region (GRFHPR) with Golden ratio approach
3. Enhancing the GRFHPR with Difference of 	Gaussian 	(DoG) and Contrast Limited 	Adaptive Histogram 	Equalization (CLAHE) 	method, DoG-CLAHE
4. Constructive features are extracted with multilayer CNN (MLCNN)
5. Identification is performed with multiclass support vector machine (SVM)
6. Various evaluation measures such as accuracy, precision, recall, F1 score, false acceptance rate (FAR), false rejection rate (FRR), and  equal error rate (EER) are computed

Journal Title: Multimodal Biometric Authentication Using Vein Patterns: A Deep Learning Approach

Journal Name: The Visual Computer
