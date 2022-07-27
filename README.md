# Jungle Cinema Movie List

<br>
<img src= "https://velog.velcdn.com/images/greenth322/post/cb0a06e4-07c0-4a60-b0b0-ee15ca5f343b/image.png" width="530px">

## 프로젝트 소개
- HTML, CSS, Sass를 이용하여 포털 사이트에서 볼 수 있는 영화관 상영 영화 목록을 응용한 페이지입니다. 

##  기술스택
| HTML |  Css| Sass|
| :---: | :----: | :----: |

- 페이지 내 여러 section마다 서로 다른 폰트 크기, 글꼴, 두께를 사용하고 있기 때문에, 폰트 유지보수가 편리하도록 Sass Mixin을 이용하여 font를 관리합니다.
- 자주 사용되는 컬러는 _root를 style sheet내에서 쉽게  관리할 수 있도록 지정하여 사용했습니다.
- Flex 레이아웃 속성과 미디어쿼리를 사용하여 손쉽게 반응형 레이아웃을 구현했습니다. 
- 피그마 디자인 시안을 보고 정확하게 구현할 수 있습니다.

## 트러블 슈팅
- 반응형을 구현할 때 footer의 sns 아이콘 이미지 스파이트를 조정하는 데 어려움이 있었습니다. 처음 PC 브라우저 화면을 기준으로 sns 아이콘을 스프라이트 방법이 편리해서 사용했는데, 모바일 디스플레이에서는 기존 사진보다 작은 크기의 이미지를 따로 준비해야 하는 번거로움이 있었습니다. 앞으로 반응형 페이지를 제작할 때, 이미지 스프라이트 사용 시 큰 사이즈와 작은 사이즈를 모두 준비해야겠다고 느꼈습니다. 

 
