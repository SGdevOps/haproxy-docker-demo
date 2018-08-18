# HAProxy-docker-demo
Docker implemented HAProxy model with 2 server Round Robin.

## Installation & Usage
1. Clone the repository.
2. Make the environment up.

  ```
    $ docker-compose up -d
  ```

3. Visit `http://127.0.0.1`. The page shows which server was  responsed.
4. Visit `http://127.0.0.1:8080` for statistics panel.
5. If you turn one of them off, the server will be kicked out after 5 hartbeat retries.

