# Vision based moon-tracker

![alt text](https://github.com/praveenkottayi/moon-tracker/blob/master/cover/moon-set.png?raw=true)
 
A simple Moon tracker based on mask-RCNN.

**The whole evolution of moon-tracker** can be found in the below link. 

https://medium.com/@praveenkottayi/i-had-a-dream-not-as-big-as-martin-luther-king-jr-but-a-little-one-34dc2cdbb1d9?source=friends_link&sk=1d1e5c82d9377d19f08446260b7730da

Customized by : Praveen Vijayan

Inspired from : https://towardsdatascience.com/object-detection-using-mask-r-cnn-on-a-custom-dataset-4f79ab692f6d

Inspired from : https://github.com/matterport/Mask_RCNN


# Suggestions : 

1. Use **Google's Colab** if you don't have a **GPU** to work with. Same code will work there easily. 
Also it will reduce the error based on the **tensorflow dependency**. 

![alt text](https://github.com/praveenkottayi/moon-tracker/blob/master/cover/moon mask dream.jpg?raw=true)

Keeping your files in Google drive and mounting the same in the colab environment. 
And just changing the working directory to the moon-tracker will be cake walk. 

https://colab.research.google.com/notebooks/io.ipynb

2. Tensorflow and keras may have some version issues. As some the function calls from **'/matterport/Mask_RCNN'** is of the old version. Create your environment accordingly else you have to modify inside the actual functions. Recommended to use **tensorflow 1.4+ and Keras 2.0.8+.** 

3. Use **labellmg** to create a mask for an image. It will give output as an **XML** file. 

![alt text](https://github.com/praveenkottayi/moon-tracker/blob/master/cover/mask_labellmg.jpg?raw=true)

4. Download and keep the **COCO weights** from 'mask_rcnn_coco.h5' in the master. 

 Link : https://github.com/matterport/Mask_RCNN/releases

5. Play with **learning_rate, epoch  and layers** ('all' , '3+', '4+' , 'heads' ) for better accuracy.

6. Notebook by default saves the trained model in **moon_model**. 
If an improved model is used while testing it can result in better accuracy. 

