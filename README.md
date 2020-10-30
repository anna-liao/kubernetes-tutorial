# kubernetes-tutorial
Adaptation of kubernetes/examples "guestbook" application

I updated the kubernetes-tutorial to include a "blog" application that uses multiple front-end web server coupled with a Redis key-value store on the backend to store the blog data. This is in https://github.com/cu-csci-4253-datacenter/kubernetes-tutorial/tree/master/05-guestbook

For examples of using Redis, see the code in python-redis/app/routes.py within that directory.

This example includes examples of:

Using database for shared data access across multiple pods in a deployment
Using service names to access e.g. databases
Using an "ingress" to provide access to the frontend without using kubectl port-forward
If you already checked out the tutorial, just do a "git pull" and you'll get the updates.

If you haven't checked out and gone through the tutorial, do so now or you'll have a bad time with lab7.
