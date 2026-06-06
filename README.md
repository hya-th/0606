# 별자리 웹포스터

별자리와 밤하늘의 분위기를 시각적으로 표현한 인터랙티브 웹포스터입니다.  
어두운 우주 배경 위에 별, 원형 궤도, 선 드로잉, 별자리 SVG 그래픽을 배치하고 CSS 애니메이션과 JavaScript를 활용해 반짝이는 별빛과 서서히 나타나는 시각 효과를 구현했습니다.

## 배포 링크

[웹포스터 보러가기](https://hya-th.github.io/finalexam/)

## 프로젝트 소개

이 프로젝트는 정적인 이미지 포스터가 아니라, 웹 환경에서 움직임과 상호작용을 경험할 수 있도록 제작한 별자리 테마 웹포스터입니다.

카시오페이아와 북두칠성 등 별자리 SVG 에셋을 활용하고, CSS의 `stroke-dasharray`, `stroke-dashoffset`, `opacity`, `transform` 애니메이션을 통해 선이 그려지는 듯한 효과와 별이 반짝이는 효과를 표현했습니다. 또한 JavaScript와 jQuery를 이용해 화면 곳곳에 별을 무작위로 생성하여 밤하늘의 깊이감을 더했습니다.

## 주요 기능

- 별자리 테마의 풀스크린 웹포스터
- 어두운 우주 배경과 반짝이는 별 효과
- SVG 선, 원, 궤도 요소의 드로잉 애니메이션
- 마우스 hover 시 별자리 그래픽이 서서히 나타나는 인터랙션
- JavaScript를 활용한 랜덤 별 생성
- GitHub Pages를 통한 정적 웹사이트 배포 

## 사용 기술

- HTML5
- CSS3
- JavaScript
- jQuery 3.7.1
- SVG
- GitHub Pages

## 프로젝트 구조

```bash
finalexam/
├── asset/
│   ├── Cassiopeia.svg
│   ├── The Big Dipper.svg
│   ├── Group 7.svg
│   ├── Group 8.svg
│   ├── ka.svg
│   └── qn.svg
├── js/
│   └── script.js
├── style/
│   ├── reset.css
│   ├── style.css
│   └── textstyle.css
├── index.html
└── README.md
