# OpenShift API for Data Protection (OADP)




1. Create secret
```bash
oc create secret generic aws-s3-creds \
--from-file=cloud=velero-config.yaml
```

2. Create data protected application
```bash
oc apply -f dataprotectedapplication.yaml
```

