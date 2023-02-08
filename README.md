# CSS-Grid

## display: grid;

![display_grid](https://user-images.githubusercontent.com/124640888/217406655-99f63ae6-aed1-430f-b343-7b57deb1c6b0.gif)


```css

    /* 가로 */
    grid-template-columns: 100px 100px 100px; 
    grid-template-columns: 1fr 3fr 2fr 1fr; /* 공간의 비율 */
    grid-template-columns: repeat(5, 100px); /* 100px 5번 반복 */
    grid-template-columns: repeat(5, 1fr); /* 1fr의 비율을 5번 반복 */

    /* 세로 */
    grid-template-rows: 100px 200px 100px 100px;
    grid-template-rows: repeat(2, 200px);
    grid-auto-rows: 150px;
    grid-auto-rows: minmax(150px, auto); /* 높이가 유동적이며 최소값이 150px */

    /* 간격 */
    grid-column-gap: 10px; /* 행(가로) 간격 */
    grid-row-gap: 10px; /* 열(세로) 간격 */
    grid-gap:10px; /* 행, 열 간격 */

    /* 병합 */
    grid-column-start: 2; /* 가로  시작점 */
    grid-column-end: 4; /* 가로 끝나는점 */

    grid-row-start: 1; /* 세로 시작점 */
    grid-row-end: 3; /* 세로 끝나는점 */
    
    grid-column: 2/3; /* 가로 시작/끝 */
    grid-row: 1/3; /* 세로 시작/끝 */

```
