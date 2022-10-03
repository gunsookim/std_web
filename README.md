# std_web

09/27 - Basic Data Type: string의 경우 '', "" 사용 
    const와 let의 차이: let - 선언 후 변수값 변경 가능, const - 중간에 값변경.
09/28 - function: argument를 통해 값을 받아 코드를 실행 가능, argument가 반드시 필요한건 아님
    return 값이 있을 경우 해당 function은 종료되며 return 반환
    console.log()는 출력만 하므로 계산과 결과 반환을 위해서는 함수를 사용
    콜론(:) - key 값에 value 값을 지정해줌(파이썬의 딕셔너리와 유사)
    var: 전에는 var을 사용했지만, 현재는 사용하지 않음. const를 주로 사용, let은 가끔 사용
09/29 - 이벤트 발생
    const title = document.querySelector("h1")
    // html에서 <h1>태그를 가진 요소들 중 가장 첫 노드를 title에 리턴. 클래스인 경우 .을, id의 경우 #을 붙임
    const x = { 함수이름: function() {} }; // == const x = {function 함수이름() {} }; 
    
    title.addEventListenter("", x.함수이름) // 해당 이벤트 발생시 x안에 있는 함수를 실행
10/02 -     
