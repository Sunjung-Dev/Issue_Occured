# Occured ISSUE - multiprocessing, process

<img width="468" alt="image" src="https://user-images.githubusercontent.com/76513889/164027358-55cb8e9c-9ac2-4b3e-b869-848a1634503f.png">

여기서 보면 메인함수에서 프로세스 3개가 동시에 돌아가는 것을 확인할 수 있음 -> 멀티프로세싱

해결하고싶었던 방법: 기존의 프로세스는 죽이고 새로운 프로세스 만드는 것 -> 프로세스를 죽이니까 파이썬 파일 자체가 실행이 안되고 아예 실행이 종료됨.
