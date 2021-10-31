# Say hello

I created a task to say (echo to the console) "hello from tekton". To apply in
OpenShift, it's `oc apply -f tasks/0000-hello.yml`. I ran the task using `tkn
task run sayhello`. It's output was visible in the openshift UI as well as
through `tkn taskrun logs`.