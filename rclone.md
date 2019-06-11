data transfer from savio to box @UC Berkeley using rclone
follow set up http://research-it.berkeley.edu/services/high-performance-computing/transferring-data-between-savio-and-your-uc-berkeley-box-0 

login to data transfer node
```
ssh $USER@dtn.brc.berkeley.edu
```

#list available remotes

```
rclone listremotes
rclone copy /filepath Box:folder
```

