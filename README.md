Erlang http api tutorial from [youtube](https://www.youtube.com/watch?v=xCjWXJ1j64M)

Setup
  $rebar get-deps

Compile and run the test
  $rebar compile && deps/etest/bin/etest-runner

Running the server
  $erl -detached -pa deps/*/ebin ebin -s fancyapi_app start

