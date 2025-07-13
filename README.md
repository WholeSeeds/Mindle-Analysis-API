# Mindle Analysis API

FastAPI 기반 민들레 데이터 분석 백엔드 프로젝트입니다.

---

## 🚀 실행 방법

### 1. 저장소 클론
```bash
git clone https://github.com/WholeSeeds/Mindle-Analysis-API.git
cd Mindle-Analysis-API
```

### 2. 가상환경 생성 및 활성화
```bash
python3 -m venv .venv
source .venv/bin/activate   # Windows는 .venv\Scripts\activate
```

### 3. 의존성 설치
```bash
pip install -r requirements.txt
```

### 4. 서버 실행
```bash
uvicorn app.main:app --reload
```

서버가 실행되면 아래 주소에서 확인할 수 있습니다:

- 기본: http://localhost:8000
- 문서: http://localhost:8000/docs (Swagger UI)
- ReDoc: http://localhost:8000/redoc
