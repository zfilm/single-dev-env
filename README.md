# single-dev-env
Example used to try a single container sample of Docker Dev Environments

## Run the application
You can simply use `make run` command or do it yourself with `go run main.go`

Those commands will start a http server listening on port `12345` 
and if your request `http://localhost:12345` you'll see the following output: 
```shell
❯ curl http://localhost:12345

          ##         .
    ## ## ##        ==
 ## ## ## ## ##    ===
/"""""""""""""""""\___/ ===
{                       /  ===-
\______ O           __/
 \    \         __/
  \____\_______/


Hello from Docker!

```

