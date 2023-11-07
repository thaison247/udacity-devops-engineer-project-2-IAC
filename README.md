# udacity-devops-engineer-project-2-IAC
Udacity Cloud DevOps Engineer - Deploy a high availability web app using CloudFormation

## Constructing Infra Steps
1. Create Networks
```
./create.sh ❯ ./create.sh udagram-network networks.yml network-parameters.json <aws_profile>
```

2. Update Networks
```
./update.sh ❯ ./create.sh udagram-network networks.yml network-parameters.json <aws_profile>
```

3. Create Servers
```
./create.sh udagram-servers udagram.yml udagram-parameters.json <aws_profile>
```

4. Update Servers
```
./update.sh udagram-servers udagram.yml udagram-parameters.json  <aws_profile>    
```

5. Delete Networks
```
./delete.sh udagram-network  <aws_profile>    
```

6. Delete Servers
```
./delete.sh udagram-servers  <aws_profile>    
```

---
## Output
Web server: http://udagra-webse-fv9jifh4gljx-1250740730.us-east-1.elb.amazonaws.com/