# 2022SV_bootcamp_backend
# 씨네21사이트 크롤링 후 몽고디비에 데이터 저장까지 구현
# 사용기술스택 및 라이브러리
  mongodb<br/>
  pymongo<br/>
  정규표현식<br/>
  beautifulsoup
# mongodb셋업
### 1.Xcode 명령줄 도구 설치
Homebrew에는 Apple Xcode의 Xcode 명령줄 도구가 필요합니다.
```
xcode-select --install
```
### 2.Homebrew 설치
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```
### 3.MongoDB 5.0 커뮤니티 에디션 설치
MongoDB Homebrew를 탭 하여 macOS 터미널에서 다음 명령을 실행하여 MongoDB 및 데이터베이스 도구에 대한 공식 Homebrew 공식을 다운로드합니다.
```
brew tap mongodb/brew
```
### 4.MongoDB Community 설치
```
brew install mongodb-community@5.0
```
### 5.Robo 3T 설치(선택사항)
[robo 3T 홈페이지](https://robomongo.org/download)<br/>
위의 링크에서 Robo 3T 설치 (Studio버전이 아니라 일반버전 설치)

# !!! 멘토님과의 상의해본결과, 사전 특성상 키-벨류 형태로 저장만 하면 되기 때문에, mongoDB 보다는, 속도 측면상, REDIS가 더 적합할 것 같다는 의견을 제시받았다. 따라서, redis로 교체 !!!

