## Notebooks on ICLR Crop diseases classification

The notebook `proto_152.ipynb` is documented and other notebook follows thesame pattern.

I findout mixup works perfectly , it gives me my top score of 0.24 without ensembles. but from my side here it seems not to work well with ensembles. 

While the other notebook without mixup gives me 0.31 and above, but with Test time Augmentation it increases the score to around 0.26 and above.

I findout that zooming actually work , especially those between 0.75-1.0 compare to 0.75 - 2.0. And training the last layer and the whole model for a longer time seems to increase the score.

Also ensembles works a lot.


