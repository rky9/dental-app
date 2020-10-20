Dev env setup:

1. Install Docker using repository method: https://docs.docker.com/engine/install/ubuntu/

2. Post-installation steps for Linux, run docker without sudo:  https://docs.docker.com/engine/install/linux-postinstall/

3. Install docker-compose for Linux: 
    3.1 https://docs.docker.com/compose/install/
    3.2 https://docs.docker.com/compose/completion/


Init project (1 time):

$ docker-compose run web bash
root@f42216e951a5:/app# npx create-react-app my-app

Run app (the above generated app)
$ docker-compose run web bash
root@6a8cff56a952:/app# cd my-app/
root@6a8cff56a952:/app/my-app# npm start

To run the main app
Run app 
$ docker-compose run web bash
root@6a8cff56a952:/app# npm install
root@6a8cff56a952:/app# npm start