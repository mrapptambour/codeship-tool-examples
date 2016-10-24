FROM busybox

ADD check_for_foo.sh .
# Why does this command fail and not contain CI* and FOO environment variables
RUN ./check_for_foo.sh
