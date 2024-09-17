# dduk-python

## 개요
- PYPI를 통해 배포되는 파이썬 라이브러리 목록 입니다.

## 실행 환경
- OS : Windows 10+
- Visual Studio Code
- Python 3.7+

## 종류
### dduk-core
> pip install dduk-core
> 코어 라이브러리

### dduk-utility
> pip install dduk-utility
> 유틸리티 라이브러리

### dduk-application
> pip install dduk-application
- 애플리케이션 런처 라이브러리
```python
from dduk.application.application import Application
def Main(argument : list[str]) -> int:
	Application.Log("started dduk-application")
	return 0 # success
```
