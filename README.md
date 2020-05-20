# moon-tracker

![alt text](https://github.com/praveenkottayi/moon-tracker/blob/master/cover/moon-set.png?raw=true)
 
A simple Moon tracker based on mask-RCNN.

**The whole evolution of moon-tracker** can be found in the below link. 

https://medium.com/@praveenkottayi/i-had-a-dream-not-as-big-as-martin-luther-king-jr-but-a-little-one-34dc2cdbb1d9?source=friends_link&sk=1d1e5c82d9377d19f08446260b7730da

Customized by : Praveen Vijayan

Inspired from : https://towardsdatascience.com/object-detection-using-mask-r-cnn-on-a-custom-dataset-4f79ab692f6d
Inspired from : https://github.com/matterport/Mask_RCNN


# Suggestions : 

1. Use **Google's Colab** if you don't have **GPU**. Same code will work there easily. 
Also it will reduce the error based on the **tensorflow dependency**. 

2. Tensowflow and keras may have some version issues. As some the function calls from **'/matterport/Mask_RCNN'** 
is of old version. Create your enviornmnet accordingly else you have to modify inside the actual functions.
Recommended to use **tensorflow 1.4+ and Keras 2.0.8+.** 

3. Use **labellmg** to create mask for a image. It will give output as an **XML** file. 

4. Download and keep the **COCO weights** from 'mask_rcnn_coco.h5' in the master. 

 Link : https://github.com/matterport/Mask_RCNN/releases

5. Play with **learning_rate, epoch  and layers** ('all' , '3+', '4+' , 'heads' ) for better accuracy.

6. Notebook by default saves the trained model in **moon_model**. 
If improved model is used while testing it can result in better accuracy. 

