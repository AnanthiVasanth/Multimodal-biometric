# Multimodal-biometric
#Biometric authentication with forehead and periocular
Steps in multimodal biometric:
1. Locating the eyes with Viola Jones algorithm
2. Segmenting the periocular and forehead region (GRFHPR) with Golden ratio approach
3. Enhancing the GRFHPR with Difference of 	Gaussian 	(DoG) and Contrast Limited 	Adaptive Histogram 	Equalization (CLAHE) 	method, DoG-CLAHE
4. Constructive features are extracted with multilayer CNN (MLCNN)
5. Identification is performed with multiclass support vector machine (SVM). 
