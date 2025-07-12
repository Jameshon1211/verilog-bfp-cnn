# verilog-bfp-cnn

Test between block-floating-point numbers and fp32 numbers inside cnn using verilog code.

modules related to bfp pregress:
1. conversion form fp32 to bfp + tb            (100%)
2. conversion from fp32 to double bfp + tb     (100%)

modules related to cnn progress:
1. convolution fusing batch normalization layer (90%)
2. reluactivation layer + tb                   (100%)
3. maxpooling layer + tb                       (100%)
4. fullyconnected layer                          (0%)
5. softmax activation layer                      (0%)
6. connection between layers                     (0%)
