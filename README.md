# AWS test

Deploy:

```
aws cloudformation create-stack \
  --stack-name test \
  --template-body file://test.yaml
```

Update:

```
aws cloudformation update-stack \
  --stack-name test \
  --template-body file://test.yaml
```

Monitor:

```
aws cloudformation describe-stacks --stack-name test
```

Debug:

```
aws cloudformation describe-stack-events --stack-name test
```


