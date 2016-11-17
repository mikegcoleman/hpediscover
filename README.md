# Discover2016 London Kiosk Demo

## Demo setup
1. Ensure the laptop has Docker for Mac or Docker for Windows installed

## Docker for Mac/Windows demo:

2. To launch the container type the following command in the terminal window

   `docker run --name discover -d -p 8080:80 mikegcoleman/discover:latest`

3. Switch to Chrome and use an ***icongito window*** to navigate to: `http://localhost:8080`

4. Click Tweet button and follow the directions (don't worry, using an incognito window means we don't save the Tweet credentials)

5. Switch back to the terminal and execute the following to commands to stop the container, and then remove it.  

    ```
    $ docker stop discover
    $ docker rm discover
    ``` 

