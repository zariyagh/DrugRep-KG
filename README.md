# DRP-KGE
Drug Repositioning Prediction using Knowledge Graph Embedding
## Abstract
Drug repositioning (DR) refers to finding new therapeutic uses for existing drugs. Current computational drug repositioning methods face data representation and negative data sampling challenges. Although, retrospective studies on the DR task attempt to utilize various representations, aggregating these features and bring drugs and diseases into a unified latent space is crucial step in prediction. Besides, the number of unknown associations between drugs and diseases, which considers negative data, is much more than known associations as positive data. It leads to an imbalanced dataset. To address these challenges, we propose the DRP-KGE framework, which applies a knowledge graph embedding method for representing drugs and diseases. Moreover, despite the typical approach that considers all unknown drug-disease associations as negative data, we select a subset of unknown associations provided the disease occurs because of the adverse reaction to a drug. It achieves AUC-ROC = 87.94% and AUC-PR=86.99%, which is higher than previous works. Moreover, we check the performance of our framework in finding related drugs for skin-related diseases: contact dermatitis and atopic eczema. DRP-KGE predicted using Beclomethasone for contact dermatitis and Fluorometholone, Clocortolone, Fluocinonide, and Beclomethasone for atopic eczema, which are examined their efficiency in other studies. Moreover, using Fluorometholone for contact dermatitis is the new suggestion of DRP-KGE that should be analyzed experimentally. 
## The model architecture

<img width="694" alt="Screen Shot 2022-09-05 at 2 56 03 PM" src="https://user-images.githubusercontent.com/53209315/194271349-9f029948-1114-44b6-a8d7-dc122993b3eb.png">
