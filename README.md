### Lesson 8 Ansible ###

This playbook create 2 nodes:

- First node build maven project boxfuse
- At second node this broject will run on web service Apache

To start:
```sh
$ ansible-playbook java.yml
```

Check: http://you-tomcat-machine-ip:8080/hello-1.0/

