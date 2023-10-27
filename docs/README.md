## 구현 기능 목록
- [ ] n대의 자동차 이름을 입력받아 저장할 기능
 - [ ] 각 자동차 이름은 쉼표로 구분 = 전체 자동차 이름 입력을 스트링으로 받는데 쉼표 (,) 로 구분
 - [ ] 예외 사항 : 자동차 이름은 5자 이하만 가능
 - [ ] 예외 사항 : 이름에 특수문자 , 띄어쓰기가 있을 때 에러 처리 ?
 - [ ] 예외 사항 : 스트링이 아닌 입력값을 받았을 때 에러 처리

-----------
- [ ] 시도할 횟수를 입력받는 기능
 - [ ] 입력받은 값 만큼 아래 3 가지 프로세스를 반복 

1. [ ] 각 자동차 별로 0 ~ 9 의 랜덤한 숫자 뽑기 기능
 - [ ] 독립적인 랜덤 값을 뽑기 위해 자동차 갯수 만큼 진행 

2. [ ] 무작위 값이 4 이상이면 전진, 4 미만이면 제자리인 것을 판단할 기능
 - [ ] 값 결정 후 각 자동차 이름에 해당 값 반영

3. [ ] 각 차수별 결과를 출력하는 기능 
 - [ ] 전진하는 자동차 이름도 같이 출력
 - [ ] 각 자동차가 값 반영 후 얼마나 전진했는지 표시
-----------

- [ ] 경주 게임 완료 후 승자를 결정하여 출력하는 기능
 - [ ] 승자가 다수일 경우 쉼표 (,) 로 구분하여 출력 ex) 최종 우승자 : A, B

### 공통 사항  
- [ ] throw 문을 사용한 에러처리는 '[ERROR]' 로 시작하여야 함 
- [ ] 프로그램 종료 시 `process.exit()`를 호출하지 않는다.
- [ ] 기능 별 테스트 필요 