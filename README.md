# x-ray-classification


In this project I attempted to train a model which could accurately classify the prescence of covid, pneumonia, or lung opacity in a chest x-ray.

I was inspired by https://github.com/priyavrat-misra/xrays-and-gradcam

I used fastai as my model training framework and trained two models using slightly different appoaches. While I was able to achieve up to 95% accuracy on test data, both models perform poorly on new images from the internet. 

Nonetheless, I learned a lot about the fastai framework (diving into the source code for many hours), considerations when training neural nets, and how to improve model performance. I also gained an appreciation for why higher level frameworks are harder to debug. 

This project provided a valuable foray into the systemic thinking required to find out the cause of strange model behavior. 

I have left the notebook heavily annotated with thoughts and experiments. It is not clean, but it reflects my thought processes. 
