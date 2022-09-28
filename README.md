### 22.09.26
#### CSS
+ 가변길이 : vh, vw
+ flex박스를 이용해서 가운데 배치.
  + 중심축 : justify-content: center;
  + 반대축 : align-items: center;
  + 중심축 결정
    + flex-direction: column; // 위에서 아래
    + flex-direction: row; // 왼쪽에서 오른쪽
  + 인라인 형식을 블럭화 : display: inline-block; 
  
1. 출력 위치
  + 내부
    + head 영역
    + body 영역 어디든
  + 외부 
    + src 속성

2. 함수 선언 방식
  + 기존
    + function 함수명() {
      실행내용;
    }
  + ES6+
    + 화살표 함수
      + contst 함수명 = () => {
        실행내용;
      }
    + 백틱문자열 사용
      문자+숫자 동시 출력 : `문자${숫자 또는 변수명}`


### 22.09.27
+ const 는 고정
+ let 은 가변
+ 변수 선언 필요 없음

1. forEach : 선아이템 후인덱스
2. for of : 선인덱스 후아이템

### 22.09.28
+ === : 정확히 일치하는가(데이터 타입까지)