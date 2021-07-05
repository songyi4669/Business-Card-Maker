# Business-Card-Make🙎‍♀️🙍‍♂️ 
https://card-maker-song.netlify.app

![cardmakergif](https://user-images.githubusercontent.com/81962246/124360068-af3f5080-dc62-11eb-9b76-c809cb3b366d.gif)


## 소개
- 리액트로 제작한 명함을 등록할 수 있는 앱입니다.

## 주요기능
1. 기존 소셜 계정으로 로그인 가능
2. 명함 정보를 직접 등록 가능
3. 등록한 명함 preview제공
4. 명함 삭제 기능
5. 재 로그인시, 기존 데이터 저장 기능


## 기술스택
이 프로젝트에 사용된 기술은 다음과 같습니다.
- React.js
- React.Hooks
- React.Router
- PostCSS
- Firebase
- Cloudinary

## 기능 상세
### 1. 기존 소셜 계정으로 로그인 가능
- Firebase로 기존 소셜 계정으로 로그인이 가능합니다.
- 로그인에 성공하면 React.Router을 사용하여 명함 등록/보기 화면으로 전환됩니다.

### 2. 명함 정보를 직접 등록 가능
- 명함 정보를 직접 입력할 수 있습니다.
- 명함 보기화면의 명함의 바탕 색상도 지정할 수 있습니다.
- Cloudinary를 이용하여 이미지 업로드가 가능합니다.

### 3. 등록한 명함 preview제공
- 명함을 add하면 바로 옆 preview에 등록한 명함이 보여집니다.
- 명함을 등록하고 수정하면 실시간으로 preview에 적용됩니다.

### 4. 명함 삭제 기능
- 등록한 명함을 Delete하면 삭제됩니다.


### 5. 재 로그인시, 기존 데이터 저장 기능
- 앱을 나가거나 로그아웃 후, 재 로그인해도 기존 데이터가 저장되어 보여집니다.


