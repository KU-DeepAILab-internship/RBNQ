# Trained Models specific information
1. EDSR without BN x2
* train dataset : Div2k
* test dataset : Urban100, Div2k(test2k, test4k)
* n_resblocks : 16
* n_feats : 64
* res_scale : 1
* epochs : 200
* Test result : 31.849dB(Urban100 x2)

2. EDSR without BN x4
* pretrained model : EDSR without BN x2
* train dataset : Div2k
* test dataset : Urban100, Div2k(test2k, test4k)
* n_resblocks : 16
* n_feats : 64
* res_scale : 1
* epochs : 100
* Test result : 25.72dB(Urban100), 27.49dB(test2k), 28.87dB(test4k)
