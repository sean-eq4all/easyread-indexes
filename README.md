# easyread-indexes
쉬운 정보 변환 솔루션 결과를 다양한 지표로 분석하기 위한 프로젝트.

## 개요
- 본 프로젝트는 쉬운 정보 변환 솔루션의 결과를 다양한 지표로 분석한다.
- 프로그램 실행 시, 본 프로젝트에서 분석할 수 있는 지표 종류를 보기 좋게 나열한다.
- 본 프로젝트는 Python으로 구성한다.

## 문서 구조
- `md/` 디렉토리에 본 프로젝트 진행에 필요한 문서를 관리한다. 단, `README.md`는 제외한다.
- 지표 종류와 설명은 `md/indexes.md`에 기록한다.

## 개발 환경
- 가상환경을 구성해 진행한다.
- 필요 라이브러리는 `requirements.txt`로 관리한다.

### 가상환경 설정
PowerShell 기준:
```bash
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements.txt
```

가상환경 종료:
```bash
deactivate
```
