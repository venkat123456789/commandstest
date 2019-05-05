# Stuff that we commanly use in devops stack

## Git commands

#### Commands for to delete the previous commits

```git rebase hard --
2,$  s/pick/g
git push --delete origin brnach_name
git push origin brnach_name
```

#### Commands for to do cherry pick the commits

```
git checkout b3d92c5 Checkout the last usable commit.
git checkout -b repair Create a new branch to work on.
git cherry-pick 77b9b82 Run through commit 3.
git cherry-pick 2c6a45b Run through commit 1.
git checkout master Checkout master.
git reset --hard b3d92c5 Reset master to last usable commit.
git merge repair Merge our new branch onto master.
git push --hard origin master Push master to the remote repo.
```

Please refer the url : https://www.clock.co.uk/insight/deleting-a-git-commit

## Ansible

#### Ansible setup and process to run and test the roles

- Create a directory as ansible workstation
- I will use a script to intall ansible 

```Script for ansible installation
```

- Once the installation is done you need to check the version of ansible
- Make sure you copy all your roles and playbooks under the ansible-wrokstation directory
- create a file called dev under the same directory
- Add the hostname in that file : hostname - host that you want to run over your ansible role
- Make sure you copy your pub key to the host before apllying the role
- we need to test that connection is established or not
- you can use this ping command to test the host connection

#### Running the ansible playbook 

- cd ansible-workstation
- ansible playbook -l hostname path_to_playbook

## Terraform

#### Commands to use for terraform

```
terraform init
terraform plan
terraform validate
terraform apply
terraform destroy
terrraform taint
```

## Kubernetes

#### commands most commonly used in k8s

- kubectl get pods  :  check the pods that are running under the default namespace
- kubectl get --all-namespaces pods : check the pods that are running under the all namespaces
- kubectl get --all-namespaces  : to show all namespaces
- kubectl get nodes  : to show all the nodes in cluster
- kubectl create -f https://k8s.io/examples/admin/namespace-prod.json  : for to ceate a sample namespace 

## Jenkins

## Readme.md

#### please find the link below for the prepare readme syntax

- https://help.github.com/en/articles/basic-writing-and-formatting-syntax
