# dduk-python

## 개요
- PYPI를 통해 배포되는 파이썬 라이브러리 목록


## 실행 환경
- OS : Windows 10+ | MacOS | Linux
- Visual Studio Code
- Python 3.7+

## 종류
### 유틸리티
#### dduk-cli-tools
- 명령줄 도구 목록
- 다운로드
	> 예정
 
### 라이브러리
#### dduk-core
- 코어 라이브러리
- 설치
	> pip install dduk-core

#### dduk-utility
- 유틸리티 라이브러리
- 설치
	> pip install dduk-utility

#### dduk-application
- 애플리케이션 런처 라이브러리
- 설치
	> pip install dduk-application
- 샘플코드
	```python
	from dduk.application.application import Application
	def Main(argument : list[str]) -> int:
		Application.Log("started dduk-application")
		return 0 # success
	```
