# OBJECT_DETECTION_YOLOv3
In the YOLO3_CUSTOM_DATASET notebook, I used YOLOv3 to detect cars in different car models. We obtained a good result and I will show you the result we obtained from there in the picture below..
![image](https://user-images.githubusercontent.com/100521892/222504169-0133a3be-3940-4e07-b86b-dc2fd5053093.png)


In other notebooks, we wanted to detect objects in the images. We used an image of a person for this purpose. The first set of outputs I want to share with you are the predictions from the object_detection_with_yolo3 notebook
![image](https://user-images.githubusercontent.com/100521892/222504740-299862d9-2b8e-498d-8ea6-39abcac9fa41.png)
![image](https://user-images.githubusercontent.com/100521892/222504789-3a2d4239-e05a-48cf-bbe8-3892e2daf2bc.png)


To reduce the number of boxes with a manual threshold without changing the confidence interval, I used the non-maximum suppression method, and its outputs are as follows:
![image](https://user-images.githubusercontent.com/100521892/222505980-bd85879f-69f6-44f3-96a9-3165b7d2ca8f.png)
![image](https://user-images.githubusercontent.com/100521892/222506022-84347435-612f-4ca3-ac96-5fcec49143f7.png)
