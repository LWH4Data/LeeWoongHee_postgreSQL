# Inserting Data
- Value를 삽입할 때에 ID를 명시할 필요 없음. (자동적으로 SERIAL 타입으로 생성됨).
- Foreign key의 값은 수동으로 넣어주어야 한다.
    - 이 경우 id를 기록하거나 메모해 두는 것이 좋다.
        - 메모해 둔 key 값을 참고해서 foreign key를 삽입하란 것.
        - (모든 튜플을 기록하라는 의미 X)
    - 후에는 자동 연결 방법을 학습할 것임.
- 값을 넣는 순서는 참조되는 테이블의 값을 먼저 삽입한 뒤, 참조하는 테이블의 값을 삽입한다.
    - 참조되는 테이블의 값이 없으면 참조가 불가하기 때문.