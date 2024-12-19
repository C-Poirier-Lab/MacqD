# MacqD-A-Deep-Learning-based-Model-for-Automatic-Detection-of-Socially-housed-Laboratory-Macaques
MacqD is a modified Mask R-CNN model that incorporates a SWIN transformer backbone for enhanced attention-based feature extraction. It robustly detects macaques in their home-cage under challenging scenarios, including occlusions, glass reflections, and overexposure to light.

## Available Models
The MacqD project provides three trained models, each developed using different datasets or training strategies.
1. MacqD - Macaque Single : This model is designed for detecting individual macaques in scenarios where only one macaque is present in the frame.
2. MacqD - Macaque Curriculum : This model employs a curriculum-based training strategy. It is initially trained on a dataset containing single macaques, followed by training on a dataset with paired macaques.
3. MacqD - Macaque Combine : This model is trained on a combined dataset that includes both single and paired macaques.
[Download Trained MacqD Models](https://www.dropbox.com/scl/fo/8pcy7ey26ocynd4isxyhd/ALRQm1qGBRh-TMW0ouxo5GY?rlkey=lxwqoso39tcpsdz91n41cjbqy&st=qq8u8vc9&dl=0)


The MacqD models were developed using the [MMDetection](https://github.com/open-mmlab/mmdetection.git) framework. For detailed installation instructions, refer to the [MMDetection documentation](https://mmdetection.readthedocs.io/en/latest/get_started.html).

