NetServer는 네트워크 라이브러리 역할로, 서버이벤트 발생시 컨텐츠 서버로 가상함수를 통해 핸들링시켜줍니다.
ChattingServer는 컨텐츠를 처리하고, NetServer의 다양한 이벤트를 받아 알맞은 로직처리를 해줍니다.
Lock이 없는 구조로 만들었기에 Interlocked계열함수, LockFree자료구조 등을 활용하였습니다.
이 과정에서 많은 멀티스레딩 문제를 직면하고 해결하면서 다양한 경험을 할 수 있었습니다.
