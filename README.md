# Figma
## 🍑 Design Token 

**디자인 토큰**  이란 보여지는 값 **(visual values)** 이며 이런 visual values들은 우리의 디자인를 구성하는 기본조각이라고 할 수 있다.  
이것들은 간단한 **데이터 컴포넌트**로 쉽게 사용가능한 **코드화된 디자인 시스템** 이다. 

### 디자인 토근을 하는 이유는, 

- design systems를 효과적으로 관리하고 design 과 development쪽에서 좀더 원할하게 소통할 수 있으며 UI 전체에서 높은 일관성을 유지하기 위해 사용한다.  
- Design Tokens 은 **'별칭 (Alias)'** 과 같은 역할을 한다.
- 이것이 필요한 이유를 설명하자면 **디자이너는 '선택'** 를 하는 것이고 선택한 것을 **개발자가 '사용'** 합니다.   
  그러니 선택한 것을 수정하게 되면 개발쪽에서는 <ins>선택된 그것이 적용된 모든 부분을 바꿔야 하는 문제가 발생하는 것입니다.</ins>  
  그래서 그 **'선택'에 별칭을 붙이고** 실제 내용을 할당합니다.  
  개발자는 그 '별칭'를 사용하기 때문에 디자이너가 해당 '별칭'의 내용을 수정해도 '별칭'은 그대로 유효하니 따로 개발쪽에서 문제가 될것이 없는것입니다. 


- Figma 스타일 및 사용자 지정 토큰을 스타일 사전 준비 json으로 내보내거나 github에 동기화합니다.



> Design tokens are visual values that construct the foundational pieces of your designs. These items must be simple data components that can easily be consumed by our living coded design system. Examples of design tokens are elements like colors, type styles, spacers, shadows, animations.    
> (출처 : https://www.headway.io/blog/design-tokens-in-figma-setting-up-your-design-system )

## 🍑 Design Tokens은 아래의 '속성'에서 생성할 수 있습니다.

- colors, opacity, shadow
- font-size, -weight , eltter-spacing, linek-height
- grids
- effects
- sizes
- spacing, media-query(break point), transition, z-index
- radius
- borders
- motion
- opacity

## 🍑 디자인 토큰에 대한 예시 
<img width="400" alt="스크린샷 2023-05-16 오후 8 20 49" src="https://github.com/PhoebeYoon/Figma/assets/48478079/ae74623b-9d16-4dd3-98af-e122f533738d">  

(출처:https://www.headway.io/blog/design-tokens-in-figma-setting-up-your-design-system)   

위의 예시처럼 컴퓨터에서 컬러의 값은 **16진수**로 표현됩니다. ( #0473df , hexa 값이라고 부릅니다. ) 이런 헥사값을 여러군데 사용하게 되면 나중에 수정해야 할때 사용된 모든 곳을 일일이 찾아 변경된 헥사값으로 수정해야 합니다.  
그런데 이 헥사값에 '별칭'을 붙이고 사용할때는 헥사값대신 **'별칭'** 을 사용하는 시스템입니다.   


개발쪽에서는 이미 이런 개념을 사용중이지만 디자인에서는 조금 생소한 개념일 것입니다.  


그리고 이렇게 별칭을 붙일때는 아래와 같은 방식으로 별칭을 만드는 것이 좋습니다. 예를들면,     
- button-primary (버튼인데 주된 역할을 한다는 의미 )   
- button-primary-disabled   ( 주된 역할을 하는 버튼인데 비활성화된 상태일때 )   
- button-blue-active  ( 파란색 버튼이고 지금 활성화된 상태 )   
- checkbox-active  ( 체크박스인데 활성화된 상태  )   
- radio-active ( 라디오버튼인데 활성화된 상태 )   
- mycomany-brand , global-blue ( 문맥에  상관없이 






