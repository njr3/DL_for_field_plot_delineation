#  DL_for_field_plot_delineation

This project is to extract fields plot from hih resolution satellite imagery

Following models are supported:

| model_name       | Base Model        | Segmentation Model |
|------------------|-------------------|--------------------|
| fcn_8            | Vanilla CNN       | FCN8               |
| fcn_32           | Vanilla CNN       | FCN8               |
| fcn_8_vgg        | VGG 16            | FCN8               |
| fcn_32_vgg       | VGG 16            | FCN32              |
| fcn_8_resnet50   | Resnet-50         | FCN32              |
| fcn_32_resnet50  | Resnet-50         | FCN32              |
| fcn_8_mobilenet  | MobileNet         | FCN32              |
| fcn_32_mobilenet | MobileNet         | FCN32              |
| pspnet           | Vanilla CNN       | PSPNet             |
| vgg_pspnet       | VGG 16            | PSPNet             |
| resnet50_pspnet  | Resnet-50         | PSPNet             |
| unet_mini        | Vanilla Mini CNN  | U-Net              |
| unet             | Vanilla CNN       | U-Net              |
| vgg_unet         | VGG 16            | U-Net              |
| resnet50_unet    | Resnet-50         | U-Net              |
| mobilenet_unet   | MobileNet         | U-Net              |
| segnet           | Vanilla CNN       | Segnet             |
| vgg_segnet       | VGG 16            | Segnet             |
| resnet50_segnet  | Resnet-50         | Segnet             |
| mobilenet_segnet | MobileNet         | Segnet             |


Example results for the pre-trained models provided :

Input Image            |  Output Segmentation Image
:-------------------------:|:-------------------------:
![](sample_images/1_input.jpg)  |  ![](sample_images/1_output.png)
![](sample_images/3_input.jpg)  |  ![](sample_images/3_output.png)


