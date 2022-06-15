# CSS Flex

CSS Flex 개념정리

### Container 속성

``` css
/* display - 보여짐 특성 */
display : flex; /* block 요소 */
display : inline-flex; /* inline 요소 */

/* flex-direction - 주축 설정 */
flex-direction : row; /* 행축(좌->우) */
flex-direction : row-reverse; /* 행축(우->좌) */
flex-direction : column; /* 열축(위->아래) */
flex-direction : column-reverse; /* 열축(아래->위) */

/* flex-wrap - 줄바꿈 여부 */
flex-wrap : nowrap; /* 줄바꿈 X */
flex-wrap : wrap; /* 줄바꿈 O */

/* justify-content - 수평 정렬방법 */
justify-content : flex-start; /* 왼쪽 정렬 */
justify-content : flex-end; /* 오른쪽 정렬 */
justify-content : center; /* 가운데 정렬 */

/* align-content - 수직 정렬방법 (2줄 이상) */
align-content : strectch;
align-content : flex-start; /* 위 */
align-content : flex-end; /* 아래 */
align-content : center; /* 중앙 */

/* align-items - 수직 정렬방법 (1줄) */
align-items : strectch;
align-items : flex-start; /* 위 */
align-items : flex-end; /* 아래 */
align-items : center; /* 중앙 */
align-items : baseline; /* 알파벳 아래로 */
```

### Items 속성

``` css
/* order - flex-items 순서 */
order : -1; /* 제일 앞 */
order : 2;
order : 17; /* 제일 뒤 */

/* flex-grow - 너비 증가 비율 */
flex-grow : 0; /* 증가비율 X */
flex-grow : 숫자; /* 숫자 비율값대로 가로폭 증가 */

/* flex-shrink - 감소 너비 비율 */
flex-shrink : 1; /* Container 줄면 요소도 줄어듬 */
flex-shrink : 숫자(감소비율); /* Container 줄면 요소 줄지 않음 */

/* flex-basis - 공간 배분 전 기본 너비 */
flex-basis : auto; /* 요소 내용(contents) 너비 */
flex-basis : 단위; /* 단위(px, em, rem) 지정 */
```






