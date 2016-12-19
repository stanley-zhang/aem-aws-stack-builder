# aem-aws-stack-builder
Cloudformation templates (yaml) for creating an AEM Stack

## Installation

Requirements
* [AWS CLI](http://docs.aws.amazon.com/cli/latest/userguide/installing.html)
* [GNU Make](https://www.gnu.org/software/make/) (optional, see Makefile to use commands instead)




## Usage

### Network Stack

Create VPC Stack:
```
make create-network-stack stack=vpc
```


Create Network Stack:
```
make create-network-stack stack=network
```


Delete VPC Stack:

```
make delete-network-stack stack=vpc
```


Delete Network Stack:
```
make delete-network-stack stack=network
```

### Compute Stack

Create Security Groups Stack:
```
make create-compute-stack stack=security-groups
```

Delete Security Groups Stack:
```
make delete-compute-stack stack=security-groups
```

## Ansible

Requirements:

* [Ansible](http://docs.ansible.com/ansible/intro_installation.html)
* [Boto](https://github.com/boto/boto)



## Configuration

Work in Progress


## Development

Requirements:
* [ShellCheck](https://github.com/koalaman/shellcheck)

Validate Cloudformation templates:
```
make validate
```

Check Shell Scripts
```
make shellcheck
```


