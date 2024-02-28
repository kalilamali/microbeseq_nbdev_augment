# Info
This repo contains a file `post_nbdev.sh` which can be run on the command line in order to set up a blank folder for SSI development through nbdev. The other files are referenced in `post_nbdev.sh` and will be aquired via `wget`. Make sure to run it in an empty PROJECT_NAME folder.

# Requirements
- conda
- git

# Usage
```bash
wget https://raw.githubusercontent.com/ssi-dk/microbeseq_nbdev_augment/main/make_nbdev_env.sh;
mkdir PROJECT_NAME;
cd PROJECT_NAME;
bash ../make_nbdev_env.sh;
```
