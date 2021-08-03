Learning Autentication


To debug the application, I used the launch.json file below. Special attention to the "program" parameter.

{
    // Use IntelliSense to learn about possible attributes.
    // Hover to view descriptions of existing attributes.
    // For more information, visit: https://go.microsoft.com/fwlink/?linkid=830387
    "version": "0.2.0",
    "configurations": [
        {
            "name": "Launch Package",
            "type": "go",
            "request": "launch",
            "mode": "auto",
            "program": "/workspaces/keycloack-go/goclient/main.go"
        }
    ]
}