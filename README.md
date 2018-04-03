# babel

```
npm init

npm install babel-cli babel-preset-es2015

```

+ 같은 디렉터리에 .babelrc 파일 생성 

```javascript
    {
        "presets" : [ "es2015" ]
    }
    // es2015 코드를 이전버전의 자바스크립트로 트랜스파일한다는것
```

+ src 디렉터리에 트랜스파일할 코드 만들고 터미널에서
```
babel src -d build
```