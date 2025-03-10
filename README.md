
# Design and Implementation of a Vision Transformer for Pneumonia Detection

Pneumonia continues to be one of the most costly diseases that affect the population, and it is also one
of the most common causes of death. However, in order to reduce the number of deaths and improve
the prognosis of patients, it is imperative that they receive a diagnosis as soon as possible. During
conventional diagnostic procedures, such as a physical examination followed by a chest x-ray, the
interpretation of these pictures is typically done manually. As a result, it is prone to errors and quite
slow. This is especially true in locations where there are a limited number of radiologists or where they
are unable to afford. In the past several years, a substantial amount of attention has been directed into
deep learning-based algorithms, particularly Convolutional Neural Networks (CNN), for the purpose
of automatically detecting pneumonia from medical images.
The results of this endeavour have been noted as being positive. CNN models, on the other hand, have
a restriction in that, because of their local receptive fields, it is impossible for them to capture long-
range dependencies in the image. Chest X-ray pictures are used in this research to demonstrate a unique
application of Vision Transformer (ViT), which was initially developed as a model for natural image
categorisation. The purpose of this application is to diagnose pneumonia. Vision transformer (ViT)
architecture makes primary use of the self-attention mechanism, which assists in the context-aware
representation of aspects of the image. This is due to the fact that in medical image analysis, irregular
patterns are frequently dispersed across the image and are located quite a distance apart from one
another. We trained a ViT model on a public cough chest X-ray database in order to accomplish this
goal while working on this project.




## Dataset
link : https://www.kaggle.com/datasets/artyomkolas/3-kinds-of-pneumonia/data