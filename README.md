# Neural-Style-Transfer
neural style transfer by eager execution  
paper: https://arxiv.org/pdf/1508.06576v2.pdf

weights used content_weight=(2)(1e3) style_weight=1e-2
style normalized by a coefficient of 0.75, instead of (height^2)x(width^2) 
considerable style transfered in just 200 iterations by mentioned hyperparameters 

layers used:
content_layers = ['block5_conv2'] 

style_layers = ['block1_conv1',
                'block2_conv1',
                'block3_conv1'
                'block4_conv1'
                'block5_conv1'
               ]
 reference : https://medium.com/tensorflow/neural-style-transfer-creating-art-with-deep-learning-using-tf-keras-and-eager-execution-7d541ac31398

# Mixed-Neural-Style-Transfer
Used three loss functions two for style image and one for content image
and tried to minimize them simultaneously

<p float="left">
  <img src="https://github.com/iamnotahumanbecauseiamabot/Neural-Style-Transfer/blob/master/results/download%20(25).png" width="200" />
  <img src="https://image.flaticon.com/icons/svg/61/61112.svg" width="50" height="150"/>
  <img src="https://github.com/iamnotahumanbecauseiamabot/Neural-Style-Transfer/blob/master/results/download%20(26).png" width="200" />
  <img src="https://i.pinimg.com/originals/b3/08/13/b30813efd2939f274b79b5c7ec050b04.jpg" width="150" height="150"/>
  <img src="https://github.com/iamnotahumanbecauseiamabot/Neural-Style-Transfer/blob/master/results/download%20(27).png" width="200" />
</p>
