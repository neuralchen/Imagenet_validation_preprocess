# Imagenet_validation_preprocess
The preprocess shell script for Imagenet validation set

Copy ```valprep.sh``` to the validation set directory of Imagenet dataset.

Then run below code to archive validation images into separate category folders:
```
cd [/path/to/imagenet/val]
chmod +x valprep.sh
./valprep.sh
```
