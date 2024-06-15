 ##  CAMSCANNER USING MATLAB APP DESIGNER

In this project, GUI is designed to scan, crop, rotate, filter the uploaded images. Below image demonstrate the interface of the app.

 ![Ekran görüntüsü 2024-06-15 211800](https://github.com/hypatiash/Camera-Scanner-with-MATLAB/assets/142400240/1c6236bf-3923-4340-a84e-e993d4b08b8e)

In this GUI design, there are elements such as tab group, axes, buttons, and drop-down menu. The axes elements are used for displaying the original and scanned images. Selecting through the tabs, the user can display and scan up to 10 images. The rotate drop-down menu helps to rotate image if needed. It has choices like 90,180,270,0,-90,-180 and - 270. After the user uploads the files using Upload Images button, the images can be seen in the tabs. Then, by clicking to the Scan button, the user can start the scanning process by selecting the edges of the image. The edges should be selected according to this order: top-left corner, bottom-left corner, bottom-right corner and top-right corner. These edges are the points that will be transform. If the user selects multiple images, user can select points of every image with a waiting time of 6 seconds. The result of the scanned image displayed as a black and white image by default. After the scanning process is completed, the user can select between the two different filter selections. And by switching through each tab, the filters can be applied to the desired image. Generally, the binarize button shows a great result but if there is a shadowed image or an image that looks un-readable with binarize button, the histogram eq. button can be used. 
Also, by switching through each tab the desired images can be saved through the download button. The app can be closed by clicking to exit button.
Below image is one of the few output examples of the app.

![image](https://github.com/hypatiash/Camera-Scanner-with-MATLAB/assets/142400240/18039a8c-2a22-43cd-8a15-d6a0ab247817)
![image](https://github.com/hypatiash/Camera-Scanner-with-MATLAB/assets/142400240/31d5caa3-6382-4348-bbdd-2ba32babdef9)

