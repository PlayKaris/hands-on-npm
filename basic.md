# NPM 기본 명령어

### npm 버전 확인
```npm -v```

### package.json 만드는 명령어
```npm init```

### 패키지 설치
```npm install```

### 패키지 특정 버전 설치
```npm install 패키지@버전```

### 특정한 저장소에 있는 패키지 설치 (통상 Github 패키지 설치시 이용)
```npm install 주소```

### 패키지 추가
##### 지역모드
```npm install --save 또는 -S```
##### 개발+지역모드
```npm install --save -dev 또는 -D```
##### 전역모드
```npm install -g```

### 설치한 패키지 업데이트
```npm update```

### npm의 중복된 패키지들 정리 (용량 확보)
```npm dedupe```

### 패키지 설명 (npm 홈페이지 좋음)
```npm docs```

### node_modules의 위치 확인
```npm root```

### 오래된 패키지 확인
- 오래됐고 + package.json 버전 범위 일치 = 빨간색,
- 오래됐고 + package.json 버전 범위 불일치 = 노란색</br>
```npm outdated```

### 패키지 조회
##### 기본
```npm ls```
##### 심화
```npm ll```
##### 패키지 존재 유무 + 어떤 패키지의 dependencies인지 확인
```npm ls [패키지명]```

### 설치된 모듈 확인(전역)
```npm ls -g --depth=0```

