    (python -c 'print "payload"'; cat -) | nc pwnable.url
    (echo payload; cat) | ./pwnable
    cat payload - | ./pwnable