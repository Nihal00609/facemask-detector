# facemask-detector
command to install required lbraries
$ pip3 install -r require.txt

to train the model
$python3 train.py --dataset dataset 
where dataset is a folder containing two folders with_mask and without_mask both containing images accordingly

detect mask using the following command 
$ python3 detect_mask_image.py --image images/pic1.jpeg
