## 딥러닝 기반 피부 질환 및 치료 비용 예측 AI 개발
> 프로젝트 목표

- AIHUB Dataset과 Unet, Yolo를 활용하여 피부 질환 위치 모델 학습
- Dataset Searching을 통해 예상 치료 비용 산출
- 모델 성능 최적화
- API화하여 애플리케이션 및 웹사이트에 적용

> 프로젝트 기여
- **Unet을 이용한 피부 질환 종류 모델 학습**: Unet 아키텍처를 사용하여 피부 질환의 종류를 학습시키는 모델을 개발했습니다.
- **피부 질환 종류 모델 평가 및 성능 개선**: 모델의 성능을 평가하고, 하이퍼파라미터 튜닝과 데이터 보강을 통해 성능을 최적화했습니다.
- **질환 진단 제공**: 원본 이미지 위에 예측된 마스크를 반투명하게 표시하여 질환 부위를 시각적으로 보여줍니다.
- **치료 방법 예측 제공**: 모델이 예측한 질환에 맞는 치료 방법을 추천합니다.
- **치료 비용 예측 제공**: 치료 방법에 따라 예상 치료 비용을 산출합니다.
- **배포**:
    - AWS EC2를 통해 웹사이트를 배포했습니다.
    - AWs Routes3을 통해 도메인을 연결하여 사용자들이 쉽게 접근할 수 있도록 했습니다.
    - To-Deep Learning 발표: 프로젝트 결과를 To-Deep Leaming 커뮤니티에 발표하여 공유했습니다.
> 배운 점 / 느낀 점
- 컴퓨터 비전 분야의 첫 도전: 이번 프로젝트를 통해 CNN(Convolutional Neural Network)에 대한 기본적인 이해를 습득했습니다.
- 모델 Output 처리 방법 습득: 컴퓨터 비전 모델의 출력을 원하는 방식으로 시각화하고 처리하는 방법을 익혔습니다.
- 자기 주도적인 프로젝트 진행: 이전에는 따라가기 급급했지만, 이번 프로젝트를 통해 스스로 문제를 파악하고 개선하는 능력을 키웠습니다.]

> 결과물
![img](/skin.jpg)

> 발표자료
[ppt]()
