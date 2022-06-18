# CityScape Segmentation with pytorch

## 개요
CityScape 데이터 셋을 이용하여 이미지 데이터에서 Segmentation Task를 수행하였습니다.

## 데이터
+ 데이터 셋은 CityScape 데이터 셋을 기반으로 합니다.
+ CityScape 데이터 셋의 Label을 35개에서 9개로 줄여서 사용했습니다.
+ 매우 큰 이미지 데이터 셋이기 때문에 사이즈를 (128, 256)으로 Resize하여 사용했습니다.

## 사용 모델
+ Resnet18을 Backbone으로 하는 UNet
+ Vgg를 Backbone으로 하는 UNet

## 성능
추후 업데이트 예정
