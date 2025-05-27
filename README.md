#  BIFF 2022

![Image](https://github.com/user-attachments/assets/fa3d171d-d6a9-4875-9a10-a382a8b9e53e)

2022 부산국제영화제 공식 사이트를 기반으로 리디자인 · 개발한 프로젝트로, 포트폴리오용으로 제작되었습니다.

## 프로젝트 개요
- **작업 기간**: 2023.02
- **진행 방식**: 개인 프로젝트 (기여도 100%)
- **배포 링크**: https://biff.vercel.app

## 기술 스택
- **Frontend**: React
- **Data Fetching**: Axios
- **Styling**: Sass
- **Animation**: Framer Motion
- **Deployment**: Vercel
- **UI Components**: Swiper, React Slick

## 주요 기능
### 1. 영화 목록 조회 (영화진흥위원회 API 연동)

![Image](https://github.com/user-attachments/assets/32912a10-da82-4e5e-8912-8bbd2b2daa16)

- `axios`를 활용해 **영화진흥위원회(KOBIS) Open API**를 호출하고, 작품 리스트를 렌더링합니다.

![Image](https://github.com/user-attachments/assets/1bac9501-750d-4aee-aa04-98d4cf77cfde)

### 2. 작품 검색 기능 (OMDb API 연동)

![Image](https://github.com/user-attachments/assets/f828132b-1061-4030-b30f-715c63af4912)

- `axios`로 **OMDb API**를 호출하여, 사용자가 검색한 키워드에 따라 작품을 조회할 수 있도록 구현했습니다.

### 3. 작품 상세 페이지 구현

![Image](https://github.com/user-attachments/assets/98ee26fb-5b93-42ae-815c-a47b93694c05)

- `react-router`의 동적 라우팅 기능을 활용해 `/detail/:id` 경로를 설정하고, 각 작품의 ID를 기반으로 세부 정보를 요청하고, 해당 데이터에 따라 상세 화면이 동적으로 구성됩니다.

