# protoc-gen-go-json

This is a fork of [protoc-gen-go-json](https://github.com/mitchellh/protoc-gen-go-json).

## Usage

```
# buf.gen.yaml
version: v1

managed:
  enabled: true

plugins:
  - name: go-json
    out: internal/proto
```
