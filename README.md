# docker-lpeg-tester
A Docker container running the [lpeg_tester](https://github.com/trink/lpeg_tester) app for testing Lua LPEG grammars for [Heka](https://github.com/mozilla-services/heka/) development.  An instance of the app is running at http://lpeg.trink.com/ and the source is available at https://github.com/trink/lpeg_tester .

Thanks, trink!


## Running the Container

`sudo docker run -d -p 8889:8889 docker-lpeg-tester`
