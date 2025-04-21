# Traffic Safety System

## 프로젝트 개요
이 프로젝트는 컴퓨터 비전과 딥러닝 기술을 활용하여 교통 안전을 모니터링하고 향상시키는 시스템입니다. YOLOv5 객체 탐지 모델을 기반으로 도로 위의 차량, 보행자 및 교통 상황을 실시간으로 분석합니다.

## 프로젝트 구조
```
TrafficSafetySystem/
├── yolov5/
│   ├── datasets/         # 학습 및 테스트에 사용되는 데이터셋
│   └── yolov5-master/    # YOLOv5 모델 구현
```

## 주요 기능
- 실시간 차량 및 보행자 감지
- 위험 상황 식별 및 경고
- 교통량 모니터링 및 분석
- 안전 규칙 위반 감지 (과속, 신호 위반 등)

## 기술 스택
- Python
- PyTorch
- YOLOv5 (객체 탐지)
- OpenCV (영상 처리)
- 딥러닝 기반 컴퓨터 비전

## 설치 방법
```bash
# 저장소 클론
git clone https://github.com/DCU-Capston/TrafficSafetySystem.git
cd TrafficSafetySystem

# 필요한 패키지 설치
cd yolov5/yolov5-master
pip install -r requirements.txt
```

## 사용 방법
```bash
# 영상 파일이나 카메라 스트림에서 객체 탐지 실행
python detect.py --source [영상 파일 경로 또는 카메라 ID] --weights [학습된 가중치 파일]
```

## 개발 계획
- 더 많은 교통 시나리오 데이터 수집 및 모델 학습
- 실시간 알림 시스템 구현
- 클라우드 기반 분석 도구 통합
- 모바일 애플리케이션 개발

## 기여하기
프로젝트에 기여하고 싶다면 다음 단계를 따르세요:
1. 이 저장소를 포크합니다.
2. 새 기능 브랜치를 만듭니다 (`git checkout -b feature/amazing-feature`).
3. 변경 사항을 커밋합니다 (`git commit -m 'Add some amazing feature'`).
4. 브랜치에 푸시합니다 (`git push origin feature/amazing-feature`).
5. Pull Request를 생성합니다.

## 라이센스
이 프로젝트는 MIT 라이센스 하에 배포됩니다.

## 연락처
프로젝트 관련 문의 사항은 GitHub 이슈를 통해 연락해주세요.
