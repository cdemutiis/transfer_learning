# transfer_learning

The data files are encoded as: 

{network}_{dataset}_100_bottleneck_features_train.p <br>
{network}_{dataset}_bottleneck_features_validation.p <br>

Sample runs of feature_extraction.py:

python feature_extraction.py --training_file resnet_traffic_100_bottleneck_features_train.p --validation_file resnet_traffic_bottleneck_features_validation.p  --epochs 50 --batch_size 256

python feature_extraction.py --training_file vgg_cifar10_100_bottleneck_features_train.p --validation_file vgg_cifar10_bottleneck_features_validation.p  --epochs 50 --batch_size 256
