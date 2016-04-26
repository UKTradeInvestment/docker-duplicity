# duplicity
Docker backup and restore as a container based on duplicity

- Backup volume to S3
- Auto-recovery a volume from S3


## environment variables
```
AWS_ACCESS_KEY_ID=tbd
AWS_SECRET_ACCESS_KEY=tbd
DUPLICITY_ARGS="--s3-use-new-style"
```

## credits
https://github.com/yaronr/dockerfile/blob/master/backup-volume-container/run.sh by "Yaron Rosenbaum"
https://github.com/cloudposse/duplicity/blob/master/sync.sh by "Erik Osterman"
