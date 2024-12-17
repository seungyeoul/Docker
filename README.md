# Docker

모든 도커 삭제하기

~~~
docker ps -aq | ForEach-Object {docker rm -f $_}
~~~

이미지 파일 다운로드

~~~
docker image pull (이미지명)
~~~

![image](https://github.com/user-attachments/assets/ccc620a8-ca65-4bf3-94fd-007562def1e2)


이미지 파일 세부(메타데이터) 정보 조회

~~~
docker image inspect (이미지명)
~~~

![image](https://github.com/user-attachments/assets/c8df9c0e-6154-4b93-88e9-4d0cb6d964d7)

컨테이너 실행

~~~
docker run -d --name {컨테이명} 이미지명
~~~

![image](https://github.com/user-attachments/assets/4060934d-58aa-41e3-a532-90b695fe88ff)
