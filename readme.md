Ng Shi Wei
A0185450E

# Task A
## Instructions to run
1. Clone from https://github.com/shiweing/docker-reverse-proxy.git
2. `cd docker-reverse-proxy`
3. Run `docker-compose build` to build the images required.
4. Run `docker-compose up -d` to run the containers.
5. Run `curl localhost:8080` to see the html file returned.
    ```html
    <!DOCTYPE html>
    <html>

    <head>
        <title>Site 1</title>
    </head>

    </html>
    ```
6. Run `curl localhost:8081` to see the html file returned.
    ```html
    <!DOCTYPE html>
    <html>

    <head>
        <title>Site 2</title>
    </head>

    </html>
    ```  