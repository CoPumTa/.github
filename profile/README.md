# 코품타: 코딩을 품은 타이머

코딩을 품은 타이머, 줄여서 **코품타**는 여러분의 슬기로운 코딩 생활을 도와줄 최적의 파트너 앱입니다.

| 홈   | 타이머                                                      | 챌린지                                                         |
| ---------------------------------------------------------- | ----------------------------------------------------------- | -------------------------------------------------------------- |
| <img src="https://github.com/CoPumTa/.github/assets/88723775/aaf66f7c-8771-4c08-ade9-5f416c2f55ab" width = 200 alt="홈 탭"> | <img src="https://github.com/CoPumTa/.github/assets/88723775/d4a9bb1a-18ef-4f1e-9ef1-d8efe03cbef1" width = 200 alt="타이머"> | <img src="https://github.com/CoPumTa/.github/assets/88723775/8780e850-a20c-4e3b-87df-7cdb56f6f6c6" width = 200 alt="챌린지 탭"> |

## 코품타에 대하여

### 여러분의 하루 코딩 시간을 측정하세요.

코딩에 몰입하기 전, 타이머를 눌러서 몰입 모드에 돌입할 수 있습니다. 몰입 모드에 진입하면 타이머가 시작되며 여러분의 현재 몰입한 코딩 시간과 오늘 몰입한 총 시간이 기록됩니다.

또한, 홈 탭에서는 몰입 랭킹, 현재 몰입하고 있는 친구들, 나의 Github Contributions 현황을 한번에 볼 수 있습니다.

| 홈                                                         | 타이머                                                      |
| ---------------------------------------------------------- | ----------------------------------------------------------- |
| <img src="https://github.com/CoPumTa/.github/assets/88723775/aaf66f7c-8771-4c08-ade9-5f416c2f55ab" width = 200 alt="홈 탭"> | <img src="https://github.com/CoPumTa/.github/assets/88723775/d4a9bb1a-18ef-4f1e-9ef1-d8efe03cbef1" width = 200 alt="타이머"> |

### 훌륭한 프로그래머가 되기 위해, 다른 사람들과 함께 챌린지에 도전하세요.

코품타 친구들과 함께 코딩 챌린지에 도전할 수 있습니다. 1일 1백준, 나만의 토이 프로젝트 만들기, 매일 꾸준히 원하는 코딩 공부하기 등, 다양한 주제로 사람들과 챌린지에 도전해보세요. 부지런히 챌린지를 수행하면서 코품타 리워드를 적립받을 수도 있습니다(해당 기능은 아직 개발 중인 기능입니다).

| 챌린지 목록                                                      | 챌린지 추가                                                      | 챌린지 추가 예시                                                      |
| ---------------------------------------------------------------- | ---------------------------------------------------------------- | --------------------------------------------------------------------- |
| <img src="https://github.com/CoPumTa/.github/assets/88723775/8780e850-a20c-4e3b-87df-7cdb56f6f6c6" width = 200 alt="챌린지 목록"> | <img src="https://github.com/CoPumTa/.github/assets/88723775/5e3a1599-88f8-46c9-8f75-164b0c49dc84" width = 200 alt="챌린지 추가"> | <img src="https://github.com/CoPumTa/.github/assets/88723775/57eda4b7-41b7-42f6-9835-bf35b7f9654d" width = 200 alt="챌린지 추가 예시"> |

### 리워드로 자신을 뽐내보세요. (구현 예정)

| 리워드                                                     |
| ---------------------------------------------------------- |
| <img src="https://github.com/CoPumTa/.github/assets/88723775/02c33900-eb56-4e97-96f3-d2f726c015e7" width = 200 alt="홈 탭"> |

몰입 시간에 비례하여 리워드를 받을 수 있습니다. 해당 리워드를 통해서는 챌린지에 도전할 수도 있고, 스토어에서 코품타 굿즈를 구매할 수도 있습니다. 멋진 디지털 굿즈를 통해 자신만의 개성적인 프로필을 꾸며보세요.

### 로그인


| 로그인                                                      |
| ----------------------------------------------------------- |
| <img src="https://github.com/CoPumTa/.github/assets/88723775/e49c47a7-1111-49a4-b3c8-8c760c2e7013" width = 200 alt="홈 탭"> |

로컬 로그인 & 회원가입, 카카오 로그인 & 회원가입을 지원합니다.

## 기술에 관하여

#### 개발 환경

- Client
  - OS: Windows 11(22H2), macOS(Ventura 13.4),
  - Target: Android
  - FrameWork: Flutter 3.10.1
  - Language: Dart
  - IDE: VSCode
  - Target Device: Galaxy Note10, Galaxy S22
  - App built with default configuration of Flutter SDK 3.10.1
- Server
  - OS: Ubuntu 20.04 LTS
  - DB: MySQL
  - Language: JS
  - Runtime evironment: nodeJS 18.12.0 LTS
  - FrameWork: ExpressJS, Sequelize, Passport
  - Communication protocol: HTTP

---

#### 클라이언트

- Flutter Framework를 채택했습니다.
- 외부 UI 라이브러리 사용을 자제하고, 자체 환경에서 다양한 디자인을 시도했습니다.
- Flutter의 Provider 상태 관리 방식을 학습하고,

#### 서버

- 벡엔드 서버는 ExpressJS를 채택했습니다.
- Sequlize 라이브러리를 활용하여 객체와 데이터베이스를 매핑했습니다.
- Passport 라이브러리를 활용하여 세션 방식의 인증을 구현했습니다.

<br>

<img src="https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white"> <img src="https://img.shields.io/badge/express-000000?style=for-the-badge&logo=express&logoColor=white"> <img src="https://img.shields.io/badge/flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white"> <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">

---

<br>
<img src="https://github.com/CoPumTa/.github/assets/88723775/584b9588-0460-4a4e-926c-194ed7586cb2" width = 220>

_소중한 코딩 토템, 윌슨을 추억하며...._

_2023년 여름_
