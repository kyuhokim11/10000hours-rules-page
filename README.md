# 1만 시간의 법칙 페이지

HTML/CSS 기초 학습 후, 주어진 시안을 기반으로 제작한 반응형 웹 페이지입니다.  
기본적인 마크업 구조와 CSS 레이아웃 설계, 그리고 시멘틱 태그 활용을 중심으로 구현했습니다.

## 📌 프로젝트 개요
- **목표**: HTML/CSS 기초 학습 후 주어진 시안에 맞춰 정적 페이지 구현
- **주요 기능**: 주어진 디자인 시안을 기반으로 한 정적 웹페이지
- **제작 기간**: 2025.08.07~08 (2일)
- **사용 기술**: HTML5, CSS3
- **배포 링크**: [GitHub Pages](https://kyuhokim11.github.io/10000hours-rules-page/)


## 📂 폴더 구조
```10000hours-rules-page/
├── index.html
├── assets/
│   ├── icons/
│   ├── images/
│   ├── fonts/
├── css/
│   ├── reset.css
│   ├── style.css
├── docs/
│   ├── issues.md/
│   ├── progress.md/ 
```
## 📸 스크린샷 (Screenshots)
1. **메인 화면** – 전체 레이아웃 및 타이틀 영역
![메인화면](https://kyuhokim11.github.io/10000hours-rules-page/assets/images/full-page.png)  
2. **메인 화면 모달** 
![메인 화면 모달](https://kyuhokim11.github.io/10000hours-rules-page/assets/images/full-page-modal.png) 
3. **모바일 브라우저 화면** – 모바일 브라우저 화면
![모바일 브라우저 화면](https://kyuhokim11.github.io/10000hours-rules-page/assets/images/full-page-mobile.png) 

---

## 💡 구현 기능 (Features)
- 시멘틱 태그를 활용한 페이지 구현
- 반응형 디자인 적용 (뷰포트 크기에 따른 레이아웃 변경)

---

## ⚠ 개발 중 겪은 문제와 해결 과정
1. **시멘틱 태그 선택의 어려움**  
   - `<div>`로만 구성하는 것이 익숙하여 계획시 혼란을 겪었으나, 접근성 문제와 가독성을 위해 `<header>`, `<main>`, `<section>`, `<footer>`를 적극적으로 활용 시도.
   
2. **텍스트와 이미지 비율 불균형**  
   - 실제 콘텐츠에서는 줄바꿈 문제나 이미지 비율 문제가 발생 → `max-width`와 `line-height`를 조정해 해결.

3. **시안에서 각 컴포넌트 위치별 여백 규칙이 일정하지 않아 작업에 어려움**  
   - 제공된 시안에서 섹션 간, 컴포넌트 간 여백(padding, margin)의 규칙성이 부족
   - 이로 인해 개발 과정에서 레이아웃 계산이 번거로웠고, 추후 유지보수 시에도 수정 범위가 넓어질 수 있는 구조가 되었음
   - 차후 작업에서는 공통 여백 규칙을 합의하여 진행한다면 작업에 효율적일 것으로 판단
![모바일 브라우저 화면](https://kyuhokim11.github.io/10000hours-rules-page/assets/images/padding-problem.png) 

4. **피그마에서 이미지 export 시 이미지 사이즈 및 확장자 고민**
   - 역할 별로 다른 이미지 확장자 사용
   - 로고/아이콘 : SVG
   - 사진/배경: png, JPG
---

## 느낀점 & 소감
- HTML/CSS만으로도 시안에 최대한 근접한 페이지를 구현할 수 있었지만, 디자인 시안의 여백 불규칙성 때문에 처음 예상보다 작업 시간이 늘어났음. 이 과정에서 여백·간격을 공통 규칙으로 잡는 것이 유지보수에 얼마나 중요한지 체감함.
- <div> 위주의 마크업 습관에서 벗어나 시멘틱 태그의 의미와 접근성을 고려하게 된 계기였음. 앞으로는 구조 설계 단계에서 시멘틱 태그를 먼저 떠올리는 습관을 들일 계획.
- 이미지 비율 조정과 반응형 디자인 구현 과정에서 max-width, line-height 등 기본 CSS 속성의 활용성을 다시 확인했고, CSS만으로도 기초적인 반응형 구현이 가능하다는 자신감을 얻음.
- 단순한 정적 페이지였지만, 마크업과 스타일링만으로도 접근성과 유지보수성을 동시에 고려하는 훈련이 되었다는 점이 의미 있었음.

## 📜 라이선스 (License)
이 프로젝트는 MIT 라이선스를 따릅니다.