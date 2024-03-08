# Image Super Resolution
Training Data link: https://www.dropbox.com/s/2hsah93sxgegsry/91-image_x2.h5?dl=0

Eval_Data link: https://www.dropbox.com/s/r8qs6tp395hgh8g/Set5_x2.h5?dl=0

Test data link: https://www.dropbox.com/s/rxluu1y8ptjm4rn/srcnn_x2.pth?dl=0

SRCNN Paper link: https://arxiv.org/pdf/1501.00092v3.pdf

To train the model: 
run the command in terminal:
python train3.py --eval-file "path/Set5_x2.h5"  

To test the data:
python test.py --weights-file "path/srcnn_x3.pth"  --scale 3
