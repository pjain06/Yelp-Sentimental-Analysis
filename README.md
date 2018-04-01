Predicted labels for restaurants based on the images posted by the users (0: good_for_lunch, 1: good_for_dinner, 2: takes_reservations, 3: outdoor_seating, 4: restaurant_is_expensive, 5: has_alcohol, 6: has_table_service, 7: ambience_is_classy, 8: good_for_kids).
Used Inception V3 neural network developed by Google (pre-trained on ImageNet data) for transfer learning.
Created 9 different classification models, one for each label of the restaurant.
Developed 3 models to apply the classification algorithms: XgBoosting, XgBoosting with clustering and ensemble learning using Neural networks to maintain relationships between different images of the same restaurant.
Also predicted images of restaurants based on the predicted labels of the test image, i.e. having the same labels as the test image.
Developed a user interface where an user could enter the URL of an image of any restaurant and it would predict the labels for that restaurant and also the similar images.
