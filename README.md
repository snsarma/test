# 3b-awscli
Steps:
- Download [awscli-exe-linux-x86_64.zip](https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip)
- `docker build --tag awscli .`
- `docker run --rm -it -label awscli bash`
