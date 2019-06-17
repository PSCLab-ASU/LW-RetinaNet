# LW-RetinaNet

This is the source code for paper Light-Weight RetinaNet for Object Detection (https://arxiv.org/abs/1905.10011)

The code is written based upon facebookresearch/detectron (https://github.com/facebookresearch/Detectron)

Some key steps to reproduce the results:
(1). Setup the detectron throught its tutorial
(2). Use the files in LW-RetinaNet to replace the original files
(3). The config file we provide is based upon training on 4 GPUs. If you have different # of GPUs, you need to adjust the learning schedules. We adopt the "linear scaling rule" as suggested in https://github.com/facebookresearch/Detectron/blob/master/GETTING_STARTED.md



