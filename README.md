# Prettier
my prettier 설정 정리

## Plugin 설치
```npm install -D prettier```

## Config 파일 생성
```
touch .prettierrc
```

.prettierrc 파일에는 아래 내용 추가
```
{
  "printWidth": 120,
  "tabWidth": 2,
  "useTabs": false,
  "semi": true,
  "singleQuote": true,
  "trailingComma": "all",
  "bracketSpacing": true,
  "arrowParens": "avoid",
  "proseWrap": "never",
  "endOfLine": "auto"
}
```
