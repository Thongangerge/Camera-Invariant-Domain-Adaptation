# 24.05.20(Mon)
- 모델 결정
  - DeepLabV3+(drn_d_54)

1. loss function: DiceLoss + FocalLoss
- mIoU: 0.4302
![val_pred_mask](../data/result/12_week_dicefocalloss_val_pred.png)

## Issue
- loss function을 dice focal loss로 변경했더니 mIoU값이 0.43으로 상승
- 모델 구조의 한계로 데이터 증강 또는 새로운 모델 도입을 고려했음
  - 새로운 AdaptSegNet 모델을 도입하기로 함
