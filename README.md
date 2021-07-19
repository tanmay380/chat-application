# chat-application

This application is designed for LINUX, there is high chance that it wont work with WINDOWS. 

This is using SOCKET programming in order to create a connection. I have used TCP protocol over UDP as TCP is more reliable than UDP in connection based things. 



## Run Locally

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd my-project
```

And then first we'll create a server

```bash
g++ Paint_server.cpp Paint_dot.cpp Paint_network.cpp -o server.exe -lGLU -lGL -lglut -lpthread -lm
```

And then first we'll create a Client

```bash
g++ Paint_client.cpp Paint_dot.cpp Paint_network.cpp -o server.exe -lGLU -lGL -lglut -lpthread -lm
```


  
