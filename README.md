# PYTHON
### [비동기 프로그래밍](https://wikidocs.net/21046)
* 멀티스레드 vs 비동기 프로그램
    * 멀티스레드 : 100 명이 100 만큼 일처리 하는 것 (예시. 각자가 맡은 일은 하나씩 처리함. 각자 자기 일을 끝내도 다른 사람의 일을 도와주지는 않는다)
    * 비동기 프로그램 : 1 명이 100 만큼 일처리 하는 것 (예시. 불량 분석을 요청한 상태에서 분석이 끝날 때까지 기다리는 것이 아니라, 다른 업무를 보다가 불량 분석 완료 되면 이어서 처리하는 방식)

* c
* asyncio : 
    * asyncio.get_event_loop()
    * asyncio.get_event_loop().run_until_complete(`func`)
    * await asyncio.get_event_loop().run_in_executor(None, `func`, `param`)
* await : 
