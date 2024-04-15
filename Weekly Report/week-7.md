# 24.04.15(Mon)
1. 테스트 데이터의 원본 image 확인
![test_image](../data/result/7_week_origin_image.JPG)
2. Base Code로 훈련(UNet-간소화)
![UNet_image](../data/result/7_week_UNet_image.png)
3. pytorch의 UNetPlusPlus로 훈련 - encoder: resnet101, loss_function: DiceLoss
![UNet_image](../data/result/7_week_UNetPlusPlus_image.png) 

## Issue
- S06-603 RTX 3070의 CUDA memory 부족
