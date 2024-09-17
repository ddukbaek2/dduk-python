# dduk-python

## 개요
- PYPI를 통해 배포되는 파이썬 라이브러리 목록
- 이와 별개로 다운로드 가능한 명령줄 도구 목록

## 목적
- 

## 실행 환경
- OS : Windows 10+ | MacOS | Linux
- Visual Studio Code 1.91+ (using Python Extend)
- Python 3.7+

## 종류
### 유틸리티 목록
 
### 현재 배포 중인 라이브러리 목록
#### dduk-core
> pip install dduk-core
- 코어 라이브러리
- 갖가지 코드 트릭 및 소소한 기능들


#### dduk-utility
> pip install dduk-utility
- 유틸리티 라이브러리
- 로깅, JSON확장 등 여러 필요한 소소한 기능들

#### dduk-application
> pip install dduk-application
- 애플리케이션 라이브러리
- 실제 파이썬으로 코드를 실행하기 위한 프레임워크
- 기본적으로 개별파일로 실행되는 형태는 코드를 복잡하게 만드므로 이를 단순화, 규격화 시키는 용도.
- 샘플코드
	```python
	from dduk.application.application import Application

	def Main(argument : list[str]) -> int:
		Application.Log("started dduk-application")
		return 0 # success
	```
