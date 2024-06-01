I had a really tough time with this assignment. I didn't have the time to come to office hours to figure out what was going wrong. 
I have spent way too many hours trying to figure this out. 

In the "no container" method with SageMaker, I basically create a model in Sagemaker StudioLab and then download
the model file and on my local machine create the scripts to be able to deploy it to heroku:
https://wine-predict-nc-aws-5bc4dd3f99dc.herokuapp.com/

When I needed to create the "container" way, that seemed even trickier. I think I'm just missing something simple, but I think I create a container, then
send it to an AWS ERC thing, which just holds the docker image. Then in SageMaker Studio Lab, I run the docker image and create the model. That actually worked, but 
the part about deploying it locally on sage maker or heroku is having problems. Basically, something in the path file isn't lining up and I've spent a long
time trying to figure out where. It's probably something super silly too, but I haven't been able to find it. 
