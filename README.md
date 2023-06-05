# setup-dream

Install and connect DReAM CLI to DReAM Cloud POC

## Usage

```yaml
    - uses: actions/checkout@v3
      with:
        fetch-depth: 0 # not mandatory but required by certain DReAM packages

    - name: Setup DReAM CLI
      uses: novodream/setup-dream@main
      with:
        token: ${{ secrets.DREAM_TOKEN }}
```
