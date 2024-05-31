For BirdIdentifier App, I have trained the model with dataset for bird images from kaggle. The dataset has around 60k images for 400 bird species. The core ML model was created using CreateML
in iOS project and trained for 15 iterations due to device limitations without any data augmentation.
Model showed the accuracy of around 70% which can be increased by adding data augmentation. 
Added are some screenshots for the results of the identification as well as the model training steps.

Model Training steps & creating an image classifier with 400 classes.
<img width="878" alt="Screenshot 2022-05-17 at 4 16 37 PM" src="https://user-images.githubusercontent.com/41720688/168794686-2f75217f-6882-4fec-89b2-ed0b5434ec90.png">
<img width="877" alt="Screenshot 2022-05-17 at 4 16 24 PM" src="https://user-images.githubusercontent.com/41720688/168794700-92adf648-ecbc-4b24-8790-313d408242b3.png">
<img width="877" alt="Screenshot 2022-05-17 at 4 15 56 PM" src="https://user-images.githubusercontent.com/41720688/168794705-ceb38fc0-43f1-4126-9476-a58aed3be60a.png">
<img width="877" alt="Screenshot 2022-05-17 at 4 15 49 PM" src="https://user-images.githubusercontent.com/41720688/168794711-d22cf44f-a0ff-4f8b-8a34-07e32a54c1a1.png">

BirdIdentifier App results:


![IMG_2582](https://user-images.githubusercontent.com/41720688/168795328-3e877b1f-b44b-4aea-8f4f-ba90ac6b8592.PNG)
![IMG_2578](https://user-images.githubusercontent.com/41720688/168795332-6c1822f0-c839-40b6-bd5a-374c75f8c6c1.PNG)
![IMG_2558](https://user-images.githubusercontent.com/41720688/168795348-9ecd1fe4-0bb1-48b6-8313-a52b766287d4.PNG)
![IMG_2555](https://user-images.githubusercontent.com/41720688/168795351-cee4034a-2de5-4676-84bb-216faf730349.PNG)
![IMG_2424](https://user-images.githubusercontent.com/41720688/168795356-0268d351-0c74-470d-9bcb-cb88574d912d.PNG)
![IMG_2538](https://user-images.githubusercontent.com/41720688/168795359-9e742179-7f0a-42a8-9739-5b05b749c8b4.PNG)



