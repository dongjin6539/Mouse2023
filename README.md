# Mouse2023
마우 효과를 사용해서 사용자가 웹 페이지에서 마우스를 움직일 때 마우스 애니메이션 효과를 구현했습니다.

javascript를 사용해서 clientX, clientY, offsetX, offsetY, pageX, pageY, screenX, screenY 메서드를 사용해서 마우스를 움직일 때의 X와 Y의 값을 구했습니다.

## MouseEffect

**mouseEffect01** : https://dongjin6539.github.io/web2023/javascript/mouse/mouseEffect01.html <br>
- css로 마우스를 해당하는 텍스트에 mouseover했을 때의 css를 만들었습니다.
- javascript로 getAttribute() 메서드를 사용해서 add 메서드, remove 메서드를 사용했습니다.

**mouseEffect02** : https://dongjin6539.github.io/web2023/javascript/mouse/mouseEffect02.html <br>
- gsap(https://greensock.com/gsap/) 라이브러리를 사용했습니다.
- script src 태그를 사용해서 https://cdn.jsdelivr.net/npm/gsap@3.12.2/dist/gsap.min.js 의 cdn 링크를 가져왔습니다.
- css로 마우스를 해당하는 텍스트에 mouseover했을 때의 active css를 만들었습니다.
- addEventListener() 메서드를 사용해서 mouseenter 메서드와 mouseleave 메서드를 사용해서 class를 설정해줍니다.

**mouseEffect03** : https://dongjin6539.github.io/web2023/javascript/mouse/mouseEffect03.html <br>
- gsap(https://greensock.com/gsap/) 라이브러리를 사용했습니다.
- script src 태그를 사용해서 https://cdn.jsdelivr.net/npm/gsap@3.12.2/dist/gsap.min.js 의 cdn 링크를 가져왔습니다.
- 마우스 조명 효과 애니메이션을 구현했습니다.

**mouseEffect04** : https://dongjin6539.github.io/web2023/javascript/mouse/mouseEffect04.html <br>
- gsap(https://greensock.com/gsap/) 라이브러리를 사용했습니다.
- script src 태그를 사용해서 https://cdn.jsdelivr.net/npm/gsap@3.12.2/dist/gsap.min.js 의 cdn 링크를 가져왔습니다.
- 마우스를 이동할 때마다 이미지를 움직이는 것을 구현했습니다.




