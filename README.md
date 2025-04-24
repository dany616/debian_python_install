# Debian Python 설치 스크립트

데비안 기반 리눅스 환경에서 Python 3.12.0을 pyenv를 통해 설치하는 자동화 스크립트입니다.

## 기능

- 필요한 의존성 패키지 설치
- pyenv 설치
- 쉘 환경 설정 자동화 (비로그인 쉘 지원)
- Python 3.12.0 설치
- 로컬 Python 버전 설정

## 사용 방법

```bash
chmod +x debian_python_setup.sh
./debian_python_setup.sh
```

## 특징

- 로그인 및 비로그인 쉘 환경 모두 지원
- .bashrc 및 .profile 파일에 자동 설정
- pyenv shims 경로 자동 추가 