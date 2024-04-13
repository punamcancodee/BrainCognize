
# BRAINCOGNIZE : AN APP FOR BRAIN TUMOR MULTICLASSIFICATION
This project, called BrainCognize, consists of a smartphone application that scans MRI brain scan images supplied by users and classifies the images as "No Tumour" if no tumour is discovered, or as one of three possible tumour types: meningioma, glioma, or pituitary. Our initial goal was to develop a machine learning model that could correctly classify these tumour types. In order to do this, we created two separate models: one that used the VGG16 architecture and the other that was a proprietary sequential Convolutional Neural Network (CNN). The bespoke sequential model performed better than its predecessor, according to subsequent performance evaluations, which is why we integrated it into our application. For smooth integration, this sequential model was serialised into an HDF5 file. 
We extended the project further by building a Django web application, which made it easier to design a Django Rest API for the Flutter frontend. Cloudinary's technology is utilised to process user-uploaded photographs and provide the backend with the corresponding image URLs. The backend uses these URLs to either classify tumours or determine whether tumours are absent.


## Author

- [@punamcancodee](https://github.com/punamcancodee)
- [@TheUndisput3d](https://github.com/TheUndisput3d?tab=repositories)




##  Skills
- Python
- OpenCV
- Pandas
- matplotlib
- Scikit learn
- CNN
- VGG-16



## Screenshots

Detected face in Images


![App Screenshot](https://github.com/punamcancodee/BrainCognize/blob/master/Image/Screenshot_2024-03-07-13-04-25-354_com.example.disease_detector.jpg?raw=true)




![App Screenshot](https://github.com/punamcancodee/BrainCognize/blob/master/Image/Screenshot_2024-03-07-14-01-07-270_com.example.disease_detector.jpg?raw=true)




![App Screenshot](https://github.com/punamcancodee/BrainCognize/blob/master/Image/Screenshot_2024-03-07-14-02-01-918_com.example.disease_detector.jpg?raw=true)



![App Screenshot](https://github.com/punamcancodee/BrainCognize/blob/master/Image/Screenshot_2024-03-07-14-02-01-918_com.example.disease_detector.jpg?raw=true)


![App Screenshot](https://github.com/punamcancodee/BrainCognize/blob/master/Image/Screenshot_2024-03-07-14-02-31-440_com.example.disease_detector.jpg?raw=true)





## License

[MIT](https://choosealicense.com/licenses/mit/)

