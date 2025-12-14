

# JPM (Java Project Manager with AI)

**JPM**은 복잡한 CLI 명령어나 설정 파일 수정 없이, **자연어(Natural Language)**로 자바 프로젝트의 패키지를 관리하고 빌드 프로세스를 제어할 수 있는 AI 기반 데스크톱 애플리케이션입니다.

"JUnit 설치해줘", "이 프로젝트 실행해"와 같이 채팅하듯 명령하면, 내장된 GPT 엔진이 의도를 파악하여 자동으로 작업을 수행합니다.

<img width="629" height="490" alt="image" src="https://github.com/user-attachments/assets/53edfb03-778c-4308-8cde-be2e3502cc0b" />


## ✨ 주요 기능 (Key Features)

  * **💬 AI 기반 자연어 명령 처리**: GPT 모델을 활용하여 사용자의 의도를 정확히 파악합니다.
  * **📦 스마트한 패키지 관리**:
      * **설치**: Maven Central을 자동 검색하여 정확한 `groupId`와 `artifactId`를 찾아 설치합니다.
      * **업데이트/삭제**: 현재 프로젝트에 설치된 라이브러리를 분석하여 안전하게 관리합니다.
  * **⚙️ 프로젝트 제어**: 빌드(Build), 테스트(Test), 실행(Run), 초기화(Init) 등의 작업을 명령어로 수행합니다.
  * **🖥️ 직관적인 UI**: JavaFX 기반의 깔끔한 채팅 인터페이스와 실시간 진행 상황(Progress) 표시 기능을 제공합니다.
  * **📝 로그 및 설정 관리**: 실행 로그 자동 저장 및 API Key 관리 기능을 제공합니다.

## 🛠️ 기술 스택 (Tech Stack)

이 프로젝트는 **Java**와 **Python**의 하이브리드 아키텍처로 구성되어 있습니다.

  * **Frontend (UI)**: JavaFX (Java 14+)
  * **NLP Engine**: Python 3.x, OpenAI API, PyInstaller
  * **Core Logic**: Java (Project Management Logic)
  * **Packaging**: `jpackage` (Native Image Bundle)

## 🚀 설치 및 실행 (Installation)

### 시스템 요구사항

  * **OS**: macOS 11+ (Intel/Apple Silicon) 또는 Windows 10/11
  * **필수**: OpenAI API Key (유효한 키 필요)

### 다운로드 및 설치

1.  [Releases](https://github.com/CAUCSE-25-1-Capstone-Design/jpm-installer/releases/tag/JPM) 페이지에서 운영체제에 맞는 설치 파일(`.dmg` 또는 `.exe`)을 다운로드합니다.
2.  설치 파일을 실행하여 애플리케이션을 설치합니다.
3.  **(macOS의 경우)** 앱을 `Applications` 폴더로 드래그하여 설치합니다. 이때 경고가 나온다면 xattr -cr /Applications/JPM.app 명령어를 사용하세요.

### 초기 설정 (Getting Started)

1.  JPM을 실행합니다.
2.  좌측 하단의 **설정(⚙️) 버튼**을 클릭합니다.
3.  **API Key 설정** 탭에서 본인의 OpenAI API Key를 입력하고 `적용`을 누릅니다.
      * *키는 로컬 시스템에 안전하게 암호화되어 저장됩니다.*

## 💡 사용 방법 (Usage)

채팅창에 다음과 같이 입력해보세요:

  * **패키지 설치**: `"Gson 라이브러리 설치해줘"`
  * **패키지 삭제**: `"Log4j 삭제하고 싶어"`
  * **프로젝트 실행**: `"지금 프로젝트 빌드하고 실행해줘"`
  * **정보 확인**: `"설치된 패키지 리스트 보여줘"`



**Contact**: dhkimm@snu.ac.kr
