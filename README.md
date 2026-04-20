# Module-6---Concurrency

## Reflection 1
on handle_connection function 

the TCP stream is wrapped in a buffered render

then the http request is read by .lines()

then convert the Result enum into String

stored it into a vector,then print the requests line from the vector
 

based on the result the expected request contents seems to be more than the module tutorial given

it has a field named "sec-ch-ua/mobile/platform", "sec-fetch-site/mode/user/dest"

## Reflection 2

![commit2](assets/images/commit2.png)
![commit2](assets/images/commit2-1.png)
![commit2](assets/images/commit2-2.png)

## Reflection 3

if and else blocks have a lot of repetition (status_line,contents,length,response)

the only thing making it different was the filename.

to refactor it we can assign values of status_name and filename to be variables