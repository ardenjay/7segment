# 7 Segment Detection

In the factory automation, we will need auto detect the number from equipment as below: 

<img src="test_images/T5.jpg" style="zoom:50%;" />

After trying faster_rcnn_inception in google object detection, I decided to implement the simple CNN model for this.

## Overall process

There are [training phase](#training phase) and [inference phase](#inference phase).

### training phase

![](http://www.plantuml.com/plantuml/png/NOp12i8m38RlVOgm-mxkw4463i638FW04baSXJOTRIe3yTrjAvLfJlc_Bt_w8EWbMgEE5YUwaC0MDCzHG6S0o2COl95HAfqAGMFTI0R4esRDKmCOu8EU2j9y_xGxs3j-TCDrKqGDq2PpmkNid4aFkg7ODLXLko9h-AzM_ujoVV1kTb6ohNl61uCYvBdm6iezSQ12ovPHS7UnkAYNwed7QCqR)

After training, it stores the model as mnist.h5 in the current directory.

### inference phase

![](http://www.plantuml.com/plantuml/png/VP2zRiCW54Ptdk9xWGonFJ5KaJfLIg8EVG4Cjp4IFmWkGz--hN7LM48Up_4nukDIM6Mkteathnu42HjIPTXV4YbJob5JAP0eoLa6ARt0s8Tbp5_GCN2iMOZLd2K-5iAvy5R4pzrngnnQD0Hp48qj6lDHDBLeugKVRPDEB_ZVyJpfzFEbtRjhXwuTktOIudQ5n7icOpKZL3zJngmA6SI0r_iTFXfosqEjVzwkZOOTZJkQ_kX2mLJllW40)