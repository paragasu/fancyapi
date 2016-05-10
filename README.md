Erlang http api tutorial from [youtube](https://www.youtube.com/watch?v=xCjWXJ1j64M)

Setup

    $git clone https://github.com/paragasu/fancyapi.git
    $cd fancyapi
    $rebar3 compile
    $rebar3 release


Running the server

    $./_build/default/rel/fancyapi/bin/fancyapi


Open your browser and go to 

    http://127.0.0.1:3000/hello/world


Still figuring out how to run the test with rebar3 ct or rebar3 eunit.
