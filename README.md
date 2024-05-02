# pvvng.github.io

[demo](https://pvvng.github.io/test_map)

## 현재 실시간 location 얻는 방법

App.js 페이지에서 useWatchLocation Hook을 사용하여 현재 위치 좌표를 받아온다.
-> 첫 mount시 받아온 위치 좌표 값이 undefiend가 아닐 경우에 redux를 사용해 store에 저장한다.
-> 30초에 한번 이 과정을 반복한다.

## 과제

2024-05-02 

1. MovingLocation page 실시간 위치 받아서 DOM 업데이트 
2. DrawLocation page mobile에서 오류 발생
3. App.js 에서 location 전송 방식 한 번 더 생각하기
