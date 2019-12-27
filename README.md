# BUILD IMAGE WITH GLUSTERFS USING PACKER

## Export your account credentials file name and project name as environment variables:

```
export ACCOUNT_FILE_NAME={{ YOUR_ACCOUNT_FILE_NAME }}
export PROJECT_ID={{ YOUR_PROJECT_ID }}
```

# To build AMI Image using packer:

```
packer validate glusterfs.json
```
 which validates the config json

 ```
 packer build glusterfs.json
 ```

 which will create the AMI image in AWS
