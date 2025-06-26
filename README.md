-----

# 🚀 WatchOTT 프로젝트

이 프로젝트는 WatchOTT 서비스의 **전체 루트(Root) 프로젝트**예요. 서비스의 백엔드 API, 프론트엔드 웹 애플리케이션 등 모든 핵심 구성 요소들을 **Git 서브모듈로 포함**하고 있답니다.

### 📋 프로젝트 시작하기 (Getting Started)

이 프로젝트를 로컬 환경에서 올바르게 시작하려면, 다음 명령어를 사용하여 **모든 서브모듈을 포함해서 한 번에 클론**해야 해요:

```bash
git clone --recurse-submodules https://github.com/ship-owner/watchott-project.git
```

-----

#### ⚠️ 이미 클론했지만 서브모듈이 비어있는 경우

만약 `git clone` 명령어를 `--recurse-submodules` 옵션 없이 실행해서 서브모듈 폴더가 비어있거나 제대로 받아지지 않았다면, 프로젝트 디렉토리로 이동한 다음 아래 명령어를 실행해주세요:

```bash
cd watchott-project # 클론된 프로젝트 폴더로 이동
git submodule update --init --recursive
```
