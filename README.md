
## Introduce
This repo will show you an example of how to communicate with CGI

## Workflow
Host will call the CGI program and send the message ("Hello world") to CGI program, 
then the CGI program will return the result to Host.

## Run
```
make
./Host
```

## Expected results
```
$ ./Host
this is parent process
this is child process
<HTML><HEAD><meta http-equiv="content-type" content="text/html;charset=utf-8">
<TITLE>I'm a example</TITLE>
<BODY>parameter: Hello world</BODY></HTML>
```
