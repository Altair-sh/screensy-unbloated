# screensy-unbloated

Screen sharing website.
Based on https://github.com/screensy/screensy but without docker, caddy, go webserver and other bloat

## Usage

1.  ```sh
    npm install
    ```
2.  ```sh
    cp default-config.json config.json
    ```
3.  Edit `config.json`
4.  ```sh
    npm run build
    npm run start
    ```
