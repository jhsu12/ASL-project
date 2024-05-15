## American Sign Language Fingerspelling recognition


This project focuses on the recognition of American Sign Language ([ASL](https://www.kaggle.com/competitions/asl-fingerspelling)) fingerspelling using an open-source model from Kaggle. I developed a real-time fingerspelling calculator based on this model, achieving a 0.5% increase in accuracy through strategic enhancements. These improvements included the application of post-processing techniques, the adoption of a smoothed Connectionist Temporal Classification (CTC) loss function, and meticulous parameter fine-tuning.

The reason why the output shows the alphabets instead of the numbers is because the model is mainly for numbers and alphabets. Thus, I replaced the operator with alphabets and noticed that some numbers have the same ASL gesture like alphabets, ex: W and 3. Therefore, I need to do some postprocess after the output. 
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/IwV3-jW15I4/0.jpg)](https://www.youtube.com/watch?v=IwV3-jW15I4)

Additionally, I expanded the model's capabilities by training it to recognize a new gesture, the Korean heart. This involved overseeing the data collection process, which included video recording and data cleansing, to ensure the data was suitable for preprocessing and effective model training. This technique can also apply to training the operator for real-time fingerspelling calculator.

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/GtP1CNFQEMM/0.jpg)](https://www.youtube.com/watch?v=GtP1CNFQEMM)








