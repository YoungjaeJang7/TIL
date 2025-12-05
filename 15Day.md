# ***12/05 Day 15***
# ***TIL (Today I Learned)***
---
### **오늘의 배운 내용**
1. `JSON-method` : JSON 객체 안에 있는 메서드를 의미함
<br>*ex)```filter: 조건에 맞는 요소 필터링, map: 각 요소 변환,```* <br>*```sort: 정렬, reduce: 값 축약...```*
2. `JSON-dynamic` : JSON 데이터로 동적 HTML 생성을 의미함
   <br>*ex)```createElement로 요소 생성, innerHTML로 내용 설정, appendChild로 DOM에 추가,```*
   <br>*```filter, sort, map 활용, foreach로 반복 처리```*
3. `DOM` : 웹 페이지를 자바스크립트로 조작할 수 있게 구조화한 객체 모델
   <br>*```[Document Onject Model]```*
4. `DOM-tree` : 노드들을 트리 구조로 연결을 의미함
   <br>*ex)```getElementById, querySelector, parentNode, children...```* 
5. `DOM-ctrl` : 자바스크립트를 사용하여 웹 페이지를 동적으로 바꾸는 것을 의미함
   <br>*ex)```appendChild, append, remove, removeChild, textContent...```*
6. `DOM-event` : DOM 요소에서 발생하는 사건(이벤트)를 의미함
   <br>*ex)```1.캡처링: 루트->타겟, 2.타겟: 실제 발생한 요소, 3.버블링: 타겟->루트```* <br>*```(버블링을 많이 쓴다고 함)```*
7. `DOM-event-ctrl` : DOM 이벤트를 제어하는 것을 의미함<br>*```[이번트 발생 감지·처리·전파·조작·제어하는 모든 과정]```*
<br>*ex)```event.stopPropagation: 전파 중단(부모 요소 이벤트 전파 방지),```*<br>*ex)```event.preventDefault: 기본 동작 취소(링크 이동...)```*
8. `DOM-event-delegation` : 하나의 부모 요소에 이벤트 리스너를 달아서, 여러 자식 요소에서 발생하는 이벤트를 처리하는 방법을 의미함
<br>*ex)```parent.addEventListener(`click`, (e) => {
   if (e.target.matches(`.child`)) {
      //처리
   }
});```*
---
오늘 배운 건 중요한 거니깐...<br>
<img src="image-8.png" alt="sheep" width="50%" height="50%">