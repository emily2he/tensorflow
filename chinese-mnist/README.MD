#README
chinese-mnist is from @burness project(https://github.com/burness/tensorflow-101/tree/master/chinese_hand_write_rec/src), thanks @burness. I notice the accuracy may be able to improve higher, so I add a new conv layer and change a ful conv layer, and also other improve. the accuracy rate is up to 99.2% and also the rete of convergence speed up much more.

## conv layer and full conv layer
 add one conv layer or improve ful conv layer all can improve. 
 add one conv layer make accuracy from 92% up to 96.1%, 
 improve ful conv layer all,  make accuracy from 92% up to 97.3%.
 but both use not improve much more.
 ## add normalization for images 
 base above, the accuracy rate is not stable, so I add a normalization for images, the accuracy rate is up to 99.2%, and the rate of convergence is speeded up much more. and the accuracy rate is much more stable, but also some other could imove to stable accuracy.
