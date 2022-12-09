# -Vehicle-breakage-detection
![Untitled (2)](https://user-images.githubusercontent.com/103991575/206710646-ff0eafa0-8e9e-4ffa-a8ef-bc042fd704d4.png)

# 💡 Topic

- **렌트카 차량 반납시 차체 외관 사진 촬영으로 파손 종류 확인**

# 📝 Summary

(주) 쏘카에서 차량 반납시 차량 이상 유무 확인을 위하여 차량 외관의 촬영을 하도록 하였고 해당 이미지로 사용 중 파손 유무와 파산 정도, 종류 등의 정보들을 확인하여 수리비를 예측하는 것을 목적으로 하는 프로젝트 였습니다. 저희는 해당 프로젝트 기간동안 파손 종류와 디텍트의 정확도를 목표로 하였고 60만장의 이미지를 학습하는 것에 주안점을 두고 프로젝트를 진행하였습니다

# 💽 Data Set

[AI-Hub](https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=realm&dataSetSn=581)

# ⭐️ Key Function

- **단안 카메라**
    - 다른 하드웨어적인 도움없이 하나의 카메라 만으로 체적 정보를 측정
- **물체 형태의 종류**
    - 직육면체와 원기둥 형태만 측정가능
    - 상하차 시스템에서는 대부분 직육면체의 박스를 사용하므로 문제가 없을 것으로 예상
    - 편의점과 마트의 경우 높이문제보다는 가로 세로의 중요성이 더 크므로 상이할 것으로 예상

# 🤚🏻 Part

- YOLO V4 model code 수정
- model fine tunning

# 🤔 Learned

- **`YOLO v4`** 모델에 대한 기본적인 이해와 활용
- 대용량 데이터( 60만장 )의 사용에서 오는 신뢰성 측정 방법과 도메인에 대한 정확한 지식 필요
- 모델 학습 전 sample data(5만장 이상)로 하이퍼 파라미터의 최적을 찾는 등의 효율적 학습 필요

# 📷 Screenshot
![Untitled (3)](https://user-images.githubusercontent.com/103991575/206710684-e9433f84-7bfd-495f-bcd5-9f524110c8ce.png)


