# engineer-test

Create a program with the following features:

## Thread 1:
  - every $INTERVAL seconds:
    - fetch http://httpbin.org/basic-auth/username/password
    - retrieve "Date" http header
    - add to queue '{"get": "$Date"}'

## Thread 2:
  - watch the queue
  - when a new "get" entry appears:
    - post the entry as JSON to http://httpbin.org/post
    - retrieve "Date" http header
    - add to queue '{"post": "$Date"}'

## Thread 3:
  - watch the queue
  - when a "post" entry is found:
    - subtract the date of the previous "get" entry: this is the $delay
    - calculate and display the $average_delay
    - calculate the $difference (in seconds) between this $delay and the $average_delay
    - display the $delay, $average_delay and $difference (+/-)

