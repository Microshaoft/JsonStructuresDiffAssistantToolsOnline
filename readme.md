# Json Structure Diff Assistant Tools Online

## Online Demo

You'd better access it Over The GFW (Great Fire Wall).

https://agreeable-flower-06c872700.1.azurestaticapps.net/

## Development Running Usage

1. Init Development Environment for using Lite-Server as Web Server.
    ```
    npm init
    ```

2. package.json Configuration for Running Web Server command line
    ```json
    {
        "scripts" : {
            "start"   : "lite-server",
            "dev"     : "lite-server",
            "crash"   : "lite-server",
            "build"   : "echo This is a Fake Building process ..."
        }
    }
    ```

3. Debug or Run Command Line.

    ```
    npm run crash
    ```
    Or
    ```
    npm run start
    ```
    Or
    ```
    npm run dev
    ```

## Special Thanks

    https://github.com/microsoft/monaco-editor

    https://github.com/substack/json-stable-stringify

    https://github.com/epoberezkin/fast-json-stable-stringify

    https://github.com/nathancahill/split

    https://github.com/kamranahmedse/driver.js

    https://github.com/knockout/knockout

    https://github.com/jquery/jquery

    https://github.com/jquery/jquery-ui

## License

MIT
