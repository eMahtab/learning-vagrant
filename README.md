# learning-vagrant
Getting started with Vagrant


1. Download VirtualBox

2. Download Vagrant

3. Add a Vagrant box
   ```
   vagrant box add hashicorp/precise32
   ```
 
4. Create a new dir and cd into it
   ```
   mkdir vagrant101
   cd vagrant101
   ```
   
5. Now initialize the vagrant box
```
   vagrant init hashicorp/precise32
   ```
   
6. Now start the box
```
   vagrant up
   ```
   
7. SSH into your vagrant box
```
   ssh vagrant
   ```
