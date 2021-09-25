## DeadLink
> 데드링크 다 찾아버렷 ✨

### 실행 방법
1. Linux에서 npm 환경 구축
```sh
$ sudo apt-get update
$ sudo apt-get install -y build-essential
$ sudo apt-get install curl
$ curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash 
$ sudo apt-get install -y node.js
$ sudo npm install -g yarn
```
2. Broken Link 찾아내는 프로젝트 링크
```sh
$ git clone https://github.com/KITRI-BoBai/broken-link-checker
```

3. 필요한 npm 라이브러리 불러오기
```sh
$ npm install broken-link-checker -g
```

4. 프로젝트 사용법 및 옵션 확인
```sh
$ blc --help
```

5. 사용방법
```sh
$ blc [웹사이트 주소] [옵션, Default: -o]
$ blc http://ce.khu.ac.kr/
$ blc http://ce.khu.ac.kr/ -ro
```