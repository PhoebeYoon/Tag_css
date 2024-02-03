##### 🍑  Front_End 과정 1단계 

## pseudo-class 와 pseudo-element
pseudo-class는  '특정상태'에 있는 요소를 선택하는 선택자로서 css 선택자로 표현할 경우 콜론(:)으로 시작합니다.
pseudo-element는 '새로운 html'을 적용한것처럼 작동합니다. css 선택자로 표현할 경우 콜론2개 (:: )로 시작합니다.

## css specificity (명시도)
css 선택자가 적용되는 우선순위를 결정하는 규칙으로 동일한 요소를 가리키는 여러가지 선택자에 적용되는 우선순위를 가리는 것으로 
표현순서에서 나중에 나오거나 구체적으로 명확하게 표현하는 선택자가 높은 우선순위를 갖습니다.   
예를들면,   
 ::first-letter,  ::first-line , ::selection   
 ::before,  ::after
* 선택자가 가장 낮은 우선순위를 가지며 < 태그선택자 < 클래스 선택자 < 아이디 선택자 < 인라인 스타일 으로 우선순위가 높아진다.
