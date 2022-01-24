# What the Heck is Ansible?

In simple terms
Ansible is a Open source tool backed by Rad hat since 2015. that gives you the ability to control and configure multiple server at a time from one single Location By SSH Key.
- [What is Ansible Under 3 Minute](https://www.youtube.com/watch?v=tWR1KXgEYxE) 

# Task and Host
- Ansible runs tasks on hosts, and all you need is SSH. In other words, Ansible runs in one place (your laptop, or a deploy box like Rundeck or Tower, or somewhere else), opens up SSH connections to your remote hosts and then runs commands directly on them.
### What is Task?
- A task can be anything from creating a bucket in AWS S3, to launching an instance in Azure, installing pip on a server, updating a config file, or simply checking the time on a remote host. In this tutorial we focus on tasks to configure a remote Ubuntu host.
### What is Host?
- The host is where the tasks get run. It can be any number of remote hosts that you have SSH access to, or localhost.

# PlayBook
- A playbook is an entirely different way of running Ansible, that is far more powerful
### What is Play?
- A play is a set of tasks mapped to a set of hosts. Plays are organised inside a text file called a playbook.



# Learning Resources :-
- [What is Ansible By IBM](https://www.youtube.com/watch?v=fHO1X93e4WA)
- [You need to Learm Ansible Right Now](https://www.youtube.com/watch?v=5hycyr-8EKs&t=874s)
- [Get Hands Dirty On Ansible without Any Installation](https://www.katacoda.com/courses/ansible)
