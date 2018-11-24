# template-terraform-aws-account

[![CircleCI](https://circleci.com/gh/tmknom/template-terraform-aws-account.svg?style=svg)](https://circleci.com/gh/tmknom/template-terraform-aws-account)
[![License](https://img.shields.io/github/license/tmknom/template-terraform-aws-account.svg)](https://opensource.org/licenses/Apache-2.0)

Terraform template for AWS Account.

## Usage

```sh
curl -fsSL https://raw.githubusercontent.com/tmknom/template-terraform-aws-account/master/install | sh -s terraform-aws-account
cd terraform-aws-account && make install
```

## Development

### Requirements

- [Docker](https://www.docker.com/)

### Configure environment variables

```shell
export AWS_ACCESS_KEY_ID=AKIAIOSFODNN7EXAMPLE
export AWS_SECRET_ACCESS_KEY=wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY
export AWS_DEFAULT_REGION=ap-northeast-1
```

### Installation

```shell
git clone git@github.com:tmknom/template-terraform-aws-account.git
cd template-terraform-aws-account
make install
```

### Makefile targets

```text
check-format                   Check format code
cibuild                        Execute CI build
format                         Format code
help                           Show help
install                        Install requirements
lint                           Lint code
upgrade                        Upgrade makefile
```

## License

Apache 2 Licensed. See LICENSE for full details.
