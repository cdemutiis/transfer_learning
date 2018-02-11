# transfer_learning

Two Data Sources: <br>
1) German Traffic Sign Dataset <br>
2) Cifar10 

The data files are encoded as: 

{network}\_{dataset}\_100\_bottleneck\_features\_train.p <br>
{network}\_{dataset}\_bottleneck\_features\_validation.p <br>

Sample runs of feature\_extraction.py:

python feature\_extraction.py --training\_file resnet\_traffic\_100\_bottleneck\_features\_train.p --validation\_file resnet\_traffic\_bottleneck\_features\_validation.p  --epochs 50 --batch\_size 256

python feature\_extraction.py --training\_file vgg\_cifar10\_100\_bottleneck\_features\_train.p --validation\_file vgg\_cifar10\_bottleneck\_features\_validation.p  --epochs 50 --batch\_size 256

Starter code provided by [Udacity](https://github.com/udacity/CarND-Transfer-Learning-Lab) 
