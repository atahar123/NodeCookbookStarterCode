# Node Cookbook

Description

## List of what installs
- NodeJs
- Nginx
- pm2 and npm

## Commands

### Test locally
Running my unit test:
```
chef exec rspec
```

Running Integration tests and closing VM:
```
kitchen test
```

### Test in AWS
Running Integration tests in AWS
```
KITCHEN_YAML=yml_file_name.yml kitchen test
```
