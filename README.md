# flex

### 메모

- flex-box에서 부모가 아닌 자식 요소에 margin을 직접 주는 것은 룰 위반
- flex-direction 기본 속성은 row이다 (reverse) 속성도 있다
- flex-box에는 main axis, cross axis가 있는데 flex-direction에 따라 달라진다
- flex-direction이 column일 때 align-items에 space-between은 사용 할 수 없다
- flex-direction이 reverse이면 justify-content의 flex-start, end 이것 또 한 반대가 된다 (주축을 유지하지만 왼쪽에서 오른쪽으로 가는 게 아니라 오른쪽에서 왼쪽으로 간다는 말 잘 쓰진 않음;)
- flex-wrap 속성은 한 줄에 할 건지 아님 줄 바꿈을 할 건지 기본은 nowrap이고 박스들의 크기를 유지하고 싶으면 wrap을 작성해주면됨 reverse도 있음
- flex-flow는 flex-direction 과 flex-wrap의 함축 버전이다
- 다중 라인을 사용하면 align-content를 사용 할 수 도 있음
- gap의 종류에는 row, column 두 가지가 있으며 gap:10px 20px;로 가능(row-gap, column-gap)
- flex 자식들은 기본적으로 순서order이 0이다. -로도 설정 가능
- align-self는 자식들에게만 적용됨
- flex-grow 캡처로 이해 (0이면 최소한 마진,패딩없이)
- flex-shink는 브라우저가 줄 어들 때 어떤걸 더 빨리 압축 할 건지를 의미함 0이면 압축 되지 않음
- flex-basis는 glow, shrink의 따라 min-width, max-width로 활용 할 수 있음 위 코드는 max-width로
  ￼
  아래 코드는 min-width로 사용 가능
  ￼![](/public/flex-wrap.png)
- flex-basis 기본 값을 주는거다. width와 다른점을 주축을 기준으로 한다.
  flex:(flex-grow) (flex-shrink) (flex-basis)

- 
