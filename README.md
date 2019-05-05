# Stuff that we commanly use in devops stack

## Git commands

#### Commands for to delete the previous commits

```
git rebase hard --
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

## Ansible commands

#### Ansible command to run the playbook

```
ansible playbook -l hostname path_to_playbook
```

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

