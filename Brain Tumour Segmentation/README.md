# Brain Tumor Image Segmentation

This project focuses on brain tumor segmentation using deep learning techniques. The task of segmenting brain tumors from MRI images plays a vital role in medical image analysis, enabling better diagnosis and treatment planning for patients.
The project employs a U-Net architecture, which is a convolutional neural network (CNN) widely used for image segmentation tasks.

## Dataset Description
The dataset used for this project is the BraTS (Brain Tumor Segmentation) dataset, available on Kaggle. The dataset includes various MRI modalities, allowing for comprehensive analysis of brain tumors.

### Dataset Details:
- **Image Dimensions**: 240×240×155 pixels
- **MRI Modalities**:
  1. T1-weighted
  2. T2-weighted
  3. T1-weighted with contrast enhancement (T1CE)
  4. Fluid-attenuated inversion recovery (FLAIR)

## Model Architecture
### U-Net Architecture
The U-Net model is a CNN designed for image segmentation tasks. The network architecture includes:
- **Encoding Layer**: Extracts features from the input image.
- **Decoding Layer**: Upsamples feature maps and generates the segmentation mask.
- **Skip Connections**: Captures fine-grained spatial details by connecting the encoding and decoding paths.
- **Fully Convolutional Layer**: Processes images of any size and produces segmentation masks of the same size.

### Key Features of U-Net:
- Symmetric architecture for efficient segmentation.
- Ability to capture both global and local features, leading to more accurate segmentation results.
