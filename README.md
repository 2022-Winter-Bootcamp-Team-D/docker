# 🐳 docker

## 리포지토리 디렉토리 구조 예시
  ```
  docker
   |
   |______ react-repo
   |        |
   |        |_____ public
   |        |         
   |        |
   |        |_____ source
   |                 
   |                  
   |______ backend
   |         |
   |         |_____ backend
   |         |        
   |         |
   |         |_____ store, user, waiting
   |                  
   |
   |______ nginx
   |
   |______ docker-compose.yml                  
  ```

## 🌱 docker리포 사용법
1. organization의 docker 리포지토리를 개인 로컬에 git clone 한다.
  - 예시) ```git clone https://github.com/2022-Winter-Bootcamp-Team-D/docker.git```

2. IDE에서 프로젝트를 열고 root디렉토리에 있는 docker-compose.yml의 위치를 확인한다.

3. iterm2(terminal - macOS)를 열고 docker 리포지토리 위치로 이동한다.
  - 예시) ```$cd ~/waiter/docker```

4. docker-compose.yml 파일을 실행시켜 이미지를 만들고 컨테이너에 담는다.
  - react, backend, nginx 구분 없이 전부 build 함.
  - 단, 도커파일이 수정되는 경우 컨테이너를 삭제하고 다시 build하면 된다.
  - 예시) ```$docker-compose up --build```

6. 컨테이너를 삭제하고 싶을 땐 다음의 명령어를 사용한다.
  - 예시) ```$docker-compose down --volumes```



## 🖥️ Frontend팀
- **react**
  - [@HAERYN](https://github.com/HAERYN)
  - [@mineii](https://github.com/mineii)
  - [@changyeonyes](https://github.com/changyeonyes)
  - [@shrewdas](https://github.com/shrewdas)
  

## 💻 Backend팀
- **Django**
  - [@aswooo](https://github.com/aswooo)
  - [@Chynmn](https://github.com/Chynmn)
  - [@ggamD00](https://github.com/ggamD00)

