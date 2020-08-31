# Clear iptables

⚠ This action is dangerous.

This GitHub action helps you clear **every** rules in every tables in iptables.

See [clear.sh](clear.sh) to find out what this action does.

## Usage

```yml
name: Example
on: push
jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - name: checkout
        uses: actions/checkout@v2
      - uses: SeanChao/clear@master
```
