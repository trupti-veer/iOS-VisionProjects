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

![IMG_2585](https://user-images.githubusercontent.com/41720688/168795312-9e1bc6d3-ac2a-427a-b298-2e5da604b925.PNG)
![IMG_2582](https://user-images.githubusercontent.com/41720688/168795328-3e877b1f-b44b-4aea-8f4f-ba90ac6b8592.PNG)
![IMG_2578](https://user-images.githubusercontent.com/41720688/168795332-6c1822f0-c839-40b6-bd5a-374c75f8c6c1.PNG)
![IMG_2535](https://user-images.githubusercontent.com/41720688/168795387-7669d04e-990b-463a-96d1-ba0e7d5c3b19.PNG)
![IMG_2534](https://user-images.githubusercontent.com/41720688/168795392-e4df54e1-f50f-4fd3-b712-b359b61d456e.PNG)
![IMG_2532](https://user-images.githubusercontent.com/41720688/168795396-6d1ac22e-9441-4f96-91b4-0f6d34ab5c2a.PNG)
![IMG_2566](https://user-images.githubusercontent.com/41720688/168795342-e6a5678d-2b93-452a-b1aa-92fa97e18d19.PNG)
![IMG_2558](https://user-images.githubusercontent.com/41720688/168795348-9ecd1fe4-0bb1-48b6-8313-a52b766287d4.PNG)
![IMG_2555](https://user-images.githubusercontent.com/41720688/168795351-cee4034a-2de5-4676-84bb-216faf730349.PNG)
![IMG_2548](https://user-images.githubusercontent.com/41720688/168795355-d2178036-de06-464c-b6a0-80991e497405.PNG)
![IMG_2424](https://user-images.githubusercontent.com/41720688/168795356-0268d351-0c74-470d-9bcb-cb88574d912d.PNG)
![IMG_2538](https://user-images.githubusercontent.com/41720688/168795359-9e742179-7f0a-42a8-9739-5b05b749c8b4.PNG)
![IMG_2537](https://user-images.githubusercontent.com/41720688/168795366-01d61640-9599-4363-9c0b-c7aab96a10e7.PNG)
![IMG_2536](https://user-images.githubusercontent.com/41720688/168795373-955cf183-7ec9-4f64-af79-a687453ace52.PNG)

