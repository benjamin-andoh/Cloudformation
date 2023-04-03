You can run either of the shell scripts (create.sh or update.sh) as:
```
./<file_name> argument_1 argument_2 argument_3
```

For example, you can run the following command:
```
./create.sh ourdemoinfra ourinfra.yml ourinfra.json
```

Troubleshoot
While running the AWS commands using either create.sh or update.sh file, if you face permission denied error, then you will have to grant the execute permission to the owner (yourself) explicitly as:
```
chmod +x update.sh 
chmod +x create.sh 
```