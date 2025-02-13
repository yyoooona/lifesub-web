# 마이구독 - 생활 구독 관리 서비스

## 프로젝트 소개
마이구독은 여러 구독 서비스를 한눈에 관리할 수 있는 서비스입니다.   
총 구독료 확인, 구독 서비스 관리, 맞춤형 구독 추천 등의 기능을 제공합니다.

## 시작하기

### 환경 설정
1. 환경변수 설정
```bash
# .env 파일을 생성하고 아래 환경변수를 설정합니다
REACT_APP_MEMBER_URL=http://localhost:8081
REACT_APP_MYSUB_URL=http://localhost:8082  
REACT_APP_RECOMMEND_URL=http://localhost:8083
```

2. 이미지 파일 준비
public/images 폴더에 필요한 이미지 파일들을 위치시킵니다
이미지 파일명은 서비스ID.png 형식이어야 합니다 (예: netflix.png)
이미지는 PNG 포맷, 투명 배경, 200x200px ~ 400x400px 크기여야 합니다

### 설치 및 실행
```
# 의존성 설치
npm install

# 개발 서버 실행 
npm start
```

### 테스트 계정
```
ID: user01  
Password: Passw0rd
```

## 주요 기능
로그인/로그아웃  
총 구독료 조회  
구독 등급별 이미지 표시  
나의 구독 서비스 목록  
지출 패턴 기반 구독 추천  
카테고리별 구독 서비스 조회  
구독 서비스 상세 정보   
구독 신청/취소  

## 기술 스택
React 18  
React Router DOM 6  
Material UI 5  
Axios  
Context API  

## 폴더 구조
```
src/
  ├── components/         # 재사용 가능한 컴포넌트
  │   ├── auth/          # 인증 관련 
  │   ├── common/        # 공통 컴포넌트
  │   ├── main/          # 메인 화면 
  │   └── subscriptions/ # 구독 서비스 관련
  ├── contexts/          # Context API 
  ├── pages/            # 페이지 컴포넌트
  ├── services/         # API 통신
  └── utils/            # 유틸리티 함수
```

## 환경 요구사항
Node.js 18 이상  
npm 9 이상  


