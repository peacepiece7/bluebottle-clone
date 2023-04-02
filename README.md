# 임시 저장용 커밋!  원본은 사무실에 있음..
# Blue bottle clone 

# 데모 관련 어쩌고 올리기

# structure
```
│  .eslintrc.cjs
│  .gitignore
│  .prettierignore
│  .prettierrc
│  devDocs.md
│  index.html // 
│  package-lock.json
│  package.json
│  README.md
│
├─dist
│      index.html
│
├─public
│  ├─images
│  └─svg
│
└─src
    │  header.js
    │  interior-view.js
    │  main.js
    │  swpier.js
    │  view.js
    │
    └─scss
            card-category.scss
            footer.scss
            header.scss
            interior-view.scss
            left-categories.scss
            main-view.scss
            main.scss
            our-story.scss
            subscription.scss
            _config.scss
```

## 상세 설명

- header, section 등 **시멘틱 태그**를 최대한 활용했습니다.
- CSS 전처리도구 **SCSS를 사용**했습니다.
- **Parcel을 사용하여 번들링** 했습니다.
- HTML, CSS로 구현하기 힘들다고 생각한 부분은 JavaScript로 구현했습니다.
- **반응형을 구현하지 않았습니다.** max width가 1278px미만일 경우 원본가 상이한 부분이 생길 수 있습니다.
- **GNB의 모든 기능이 구현되지 않았습니다**. 원본과 동일하게 동작하지 않을 수 있습니다.

## 궁금한 점 & 주로 봐주셨으면 하는 점 

- 접근성을 고려해서 wai-aria를 최대한 활용해 봤는데 (bluebottle사이트에 aria관련 속성이 많았습니다.) 이와 관련하여 봐주셨으면 좋겠습니다.
- 클래스, 변수명이 어색하거나 잘못된 부분은 없는지 봐주셨으면 좋겠습니다.
- SCSS를 사용하는 방법 중 잘못된 부분이나 구조를 개선할 수 있는 점이 있는지 봐주셨으면 좋겠습니다.
- HTML, CSS과제 이지만 JavaScript도 개선할 부분이나 잘못된 점을 봐주셨으면 좋겠습니다.