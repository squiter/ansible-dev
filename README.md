# Ansible Dev

My ansible playbook to build my development environment with Homebrew and Homebrew Cask recipes and my [dotfiles](https://github.com/squiter/dotfiles).  

## Ansible

This repository need Ansible to run.  

### Installation

Install pip:

```
sudo easy_install pip
```
Then, install Ansible:

```
sudo pip install ansible --quiet
```

## Running my Playbook

Clone this repo in any place:

```
git clone git@github.com:squiter/ansible-dev.git
```

Enter in directory:

```
cd ansible-dev
```

And run the magic command:

```
ansible-playbook -i inventory/hosts osx.yml
```

Well done dude! Your new OSX is running awesome!