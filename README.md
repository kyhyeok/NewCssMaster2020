# NewCssMaster2020

노마드에서 제공하는 새로운 CSS Master 수업

## flex는 많이 해봤으니까 (flex는 유연함)

1. align-sled and order

- 이 두개는 child element에서만 적용된다.

2. warp nowrap

- flex는 기본적으로 nowrap이여서 element의 width이 벙위를 넘어가도 부모 element box안에 우겨 넣는데.
- child의 width이나 height를 유지 하려면 flex-wrap: wrap을 해야 한다.

3. flex-grou and flex-shrink

- 이 두개는 반응형으로 할 때 좋은가 보다

4. flex-basis

- flex-basis는 main-axis의 크기를 정해준다.

## grid(grid는 격자)

1. no grid life

- flex박스는 부모요서에서 정한 property가 자식 element에게 지나치게 영향을 많이 주기 때문에 문제가 생길 수 있다.

2. Grid Basic Concepts

- display: grid를 하면 f12(개발자도구)를 누르고 보면 줄이 보인다.
- grid-template-columns는 자식 부모로 부터 grid가 적용된 자식 element에게 width을 주는 것 (이때 순서대로 주면 된다.) 좀 헛길리네
- grid-template-rows는 height의 크기를 준다
- column-gap은 가로에 공간 row-gap은 세로의 공간 그냥 gap을 하면 가로세로 공간을 준다.
- grid-template-columns와 grid-template-rows 화면 안에 배열??이 맞으면 자동으로 맞춰서(뭔소리야...) 크기를 잡아준다.

3. Grid Template Areas

- grid는 width이나 height 없이 grid의 자식 element에서 줄 수 있다.
- grid-template-columns와 grid-template-rows를 통해 줄 수 있지만 좀 더 우아하게 해보자
- grid-template-columns:repeat(4, 200px) 첫 번째 는 갯수, 두 번째는 크기
- grid-template-rows:repeat(4, 200px) 첫 번째 는 갯수, 두 번째는 크기
- grid-template-area는 눈에 잘 보이게 layout 디자인을 해준다.
- grid-template-areas는 부모 요소에 적용하고
- grid-area는 자식 요소에 적용한다.

4. Rows and Columns

-
