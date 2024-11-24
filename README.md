# llama-server-binaries
Compiled llama server binaries

Please find the downloads at https://github.com/avdg/llama-server-binaries/releases.
The release notes also includes compilation information and references to the original code.

## Running the llama server from the commandline

```
./llama-server.exe --model <path to model>
```

Once the server is running, the server should be available at `localhost:8080`

You can add more options, which you can see if you run `./llama-server.exe --help`

Most important settings:
- If you want to change the port where the server is available at, add something like `--port 8081`
- If you want to make the server available on the network, add `--host 0.0.0.0`
- If you want to host your own files from the build-in webserver, add `--path <path to custom root web folder>`
- If you want to manually select the gpu on where to run at, add `--main-gpu <number of the gpu>`
