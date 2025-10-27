# Print Message Action

This GitHub Action prints a custom message to the workflow logs.

## Inputs

| Name    | Description         | Required |
|---------|---------------------|----------|
| message | The message to echo | ✅ Yes   |

## Example

```yaml
steps:
  - name: Print a message
    uses: dsp-testing/print-message-action@v1
    with:
      message: "Hello from my custom action!"
```

Commit 2
