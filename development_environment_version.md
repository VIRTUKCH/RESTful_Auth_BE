# 개발 환경 버전

## 1. 가상 환경 만들기
```bash
# 가상 환경 생성
python -m venv my_env
```

### 가상 환경 활성화
```bash
# 가상 환경 활성화
source my_env/bin/activate
```

## 2. RESTful API 위한 라이브러리 설치
```bash
pip install django djangorestframework
```

## 3. 인증 및 인가 위한 라이브러리 설치
```bash
pip install djangorestframework-simplejwt
```

## 4. OAuth 2 위한 라이브러리 설치
```bash
pip install django-oauth-toolkit
```

## 5. .env 파일 설정 위한 라이브러리 설치
```bash
pip install python-decouple
```

## 6. 교재에 등장하는 