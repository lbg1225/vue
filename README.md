
# Vue Vite

## 기본설치
1. Vue VS Code Extension Pack 설치
    - Ctrl + Shift + P 
      - Preferences: Open User Setting(코드라인 마지막 생성 세미콜론 자동삭제)
        - Search setting -> prettier 검색
        - Prettier: Semi 항목 Disable
        - Prettier: Single Quite 항목 Enable

2. Node Js 설치

3. Vue DevTools 설치 및 실행
    - npm install -g @vue/devtools
    - vue-devtools

4. Bootstrap5 및 Popper설치
    - npm install -g bootstrap
    - npm install -g @popperjs/core 
    - npm install -g popper.js

5. 프로젝트 생성
   - npm init vite hello-world-vite2
   - cd hello-world-vite2
   - npm install
   - npm run dev
   - npm run build
   - npm run preview

## Vue
1. index.html -> src/main.js -> src/App.vue
2. *.vue : single file component
    - <templete></templete> : Dom영역
    - <script setup></script> : Script영역
    - <style></style> : CSS영역
3. npm install path  