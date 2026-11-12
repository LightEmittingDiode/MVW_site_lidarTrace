# LiDAR 차량 추적 시각화

LiDAR 포인트와 차량 추적 결과를 브라우저에서 탐색하는 웹사이트입니다. IMU 보정 결과를 포함한 시연 화면을 제공합니다.

**[사이트 바로가기](https://lightemittingdiode.github.io/MVW_site_lidarTrace/car_tracking_2300_6700_imu_fixed/?frame=4980)**

## 저장소 구성

- `index.html`: 사이트 진입 화면
- `car_tracking_2300_6700_fixed/`: 차량 추적 시각화 자료
- `car_tracking_2300_6700_imu_fixed/`: IMU 보정 결과를 포함한 시각화 자료
- `points/`: 시각화에 사용하는 포인트 데이터
- `fonts/`, `plotly.min.js`: 웹 화면에 포함된 표시 자산

## 사용 방법

위 사이트 링크를 열고 프레임을 이동하며 포인트와 추적 결과를 확인합니다. 링크의 `frame=4980`은 시연 시작 프레임입니다. 저장소의 정적 파일을 로컬 웹 서버에서 제공해 실행할 수도 있습니다.

이 화면은 기록된 데이터와 추적 결과의 시각화입니다. 표시된 결과를 검증된 실시간 주행 안전 판정으로 해석하지 마세요.
