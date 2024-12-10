# Docker

모든 도커 삭제하기

docker ps -aq | ForEach-Object {docker rm -f $_}
