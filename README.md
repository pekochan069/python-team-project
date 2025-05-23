# 파이썬 환경 만들기

## [uv](https://astral.sh/uv)

### 설치

```sh
winget install astral-sh.uv                     # 윈도우
curl -LsSf https://astral.sh/uv/install.sh | sh # 맥, 리눅스
```

### 프로젝트 만들기

```sh
mkdir {project-name}
cd {project-name}

uv init
```

### 패키지 설치

```sh
uv add {package}
```

### 프로젝트 환경 동기화

```sh
git clone https://github.com/pekochan069/python-team-project
cd python-team-project

uv sync
```
