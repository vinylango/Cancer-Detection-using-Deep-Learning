𝗟𝘂𝗻𝗴 𝗮𝗻𝗱 𝗖𝗼𝗹𝗼𝗻 𝗖𝗮𝗻𝗰𝗲𝗿 𝗗𝗲𝘁𝗲𝗰𝘁𝗶𝗼𝗻 𝘂𝘀𝗶𝗻𝗴 𝗗𝗲𝗲𝗽 𝗟𝗲𝗮𝗿𝗻𝗶𝗻𝗴


In the fight against cancer, early detection and accurate diagnosis are crucial. Machine learning and deep learning technologies have significantly advanced this effort, especially in detecting lung and colon cancers. These technologies excel at analyzing medical imaging and patient data, offering exceptional precision and transforming traditional diagnostic methods. By leveraging algorithms to spot patterns and anomalies in imaging data, healthcare providers can identify cancers at earlier stages, improving the chances of successful treatment and enhancing patient survival.


Deep learning models, such as convolutional neural networks (CNNs), have revolutionized medical image analysis. For lung cancer, these models accurately interpret CT scans, detecting subtle signs of malignancy that may be overlooked by humans. Similarly, for colon cancer, deep learning algorithms can identify polyps and precancerous lesions in endoscopic images with high precision. These advancements not only boost diagnostic accuracy but also reduce the workload on radiologists and pathologists, allowing them to concentrate on complex cases and treatment planning. Integrating these technologies into clinical practice represents a significant leap forward in personalized medicine, offering the potential to save lives and improve care quality.


Over the past few days, I have dived into testing the power of different CNN architectures in detecting a person's Lung and Colon Cancer status based on computerized CT scans. I have used publicly available kaggle Lung and Colon CT scan datasets (https://lnkd.in/dz_n_pYY). I started by implementing a custom CNN as a baseline model and with curiosity of leveraging the power of transfer learning, I tested two other pre-defined CNN architectures: MobileNetV2 and DenseNet169. It is amazing that all of these models achieved an accuracy of over 97% on the test set. This accuracy further improved to as high as 99.8% by creating an ensemble prediction of all the three models. An ensemble was created by stacking their predictions and using Microsoft's AutoML (FLAML)  to search for an optimized final learner. For those eager to explore further, I have attached the notebook in pdf for your use. As always, comments for enrichment are much welcomed.