# Readme

### Up Container
Up the container with the following command. Be sure to fill in the `<username>` and `<password>` parameters.

```
ansible-playbook start.yml -i inventory.txt --extra-vars "username=<username> password=<password>"
```

Log the container with the following command
```
docker logs -f bitcoind-node
```

### Stop and Destroy container
Stop and destroy the container with the following command.

```
ansible-playbook stop.yml -i inventory.txt
```
