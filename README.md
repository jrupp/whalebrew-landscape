# whalebrew-landscape
Dockerized form of https://github.com/coinbase/terraform-landscape with labels for [Whalebrew](https://github.com/bfirsh/whalebrew)

## Requirements

 * [Whalebrew](https://github.com/bfirsh/whalebrew)

## Installation

```bash
whalebrew install jrupp/whalebrew-landscape
```

## Usage

Pipe the output of `terraform plan` into `landscape` to reformat the output.

```bash
terraform plan ... | landscape

