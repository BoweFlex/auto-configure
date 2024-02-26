# Auto-configure
This repository consists of two things:
- An ansible playbook
- a private submodule containing encrypted ssh keys

## Usage
This project should allow a relatively short list of steps for setup.

1. Open terminal
2. Install ansible, i.e. `sudo apt install ansible -y`
3. Clone this repository with http and enter password.
4. Change directory into this directory and run playbook.
  Installing ssh keys requires --ask-vault-pass, and I recommend using --ask-become-pass to be safe.

## Disclaimers
Most, if not all of these steps, are pretty specific to my needs and configuration. You are more than welcome to fork and adjust this to your own needs, but I make no guarantees that it will work for other usernames etc without any adjustment.

I tried to make sure that most of the ansible modules being used would work regardless of the linux flavor being used, however at this time this has only been tested on Pop!_OS.
