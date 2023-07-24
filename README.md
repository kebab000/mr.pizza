# Mr.pizza 클론 사이트 만들기
<img src="https://raw.githubusercontent.com/kebab000/mr.pizza/main/images/p1.png" />

- 이 사이트는 피자 브랜드 Mr.pizza의 홈페이지의 디자인을 모방하여 만든 사이트입니다.
- 이 작업을 통해 HTML과 CSS, JAVASCRIPT에 익숙해지고 WebStandard에 익숙해지는 시간을 가졌습니다.

- Live Demo : https://kebab00-mrpizza.netlify.app/

# 사용된 메서드
document.querySelector(): 주어진 셀렉터와 일치하는 문서 내 첫 번째 요소를 반환합니다.
document.querySelectorAll(): 주어진 셀렉터와 일치하는 문서 내 모든 요소를 NodeList로 반환합니다.

element.addEventListener(event, callback): 이벤트가 발생했을 때 특정 요소에 콜백 함수를 연결합니다.
element.classList.toggle(className): 요소의 클래스 중에 지정된 클래스 이름이 있으면 제거하고, 없으면 추가합니다.
element.classList.add(className): 요소에 지정된 클래스 이름을 추가합니다.
element.classList.remove(className): 요소에서 지정된 클래스 이름을 제거합니다.

element.cloneNode(deep): 요소를 복사하여 새로운 노드를 생성합니다. deep 매개변수가 true이면 하위 요소도 모두 복사합니다.

setInterval(callback, delay): 일정한 시간 간격으로 반복해서 콜백 함수를 실행합니다.
setTimeout(callback, delay): 지정된 시간 후에 콜백 함수를 한 번 실행합니다.

element.style: 요소의 인라인 스타일 속성에 접근합니다.
element.style.transform: 요소의 변환(transform) 스타일 속성을 설정하거나 가져옵니다.
element.style.transition: 요소의 전환(transition) 스타일 속성을 설정하거나 가져옵니다.
element.clientWidth: 요소의 내용 너비를 가져옵니다. 패딩을 포함하지 않습니다.
element.firstElementChild: 요소의 첫 번째 자식 요소를 가져옵니다.