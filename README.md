# summary-action
Write a summary in Markdown

## Examples

```yaml
steps:
  - uses: johngeorgewright/summary-action@v1.0.0
    with:
      summary: |
        # H1

        paragraph

        - item 1
        - item 2
        - item 3

        | Heading 1 | Heading 2 |
        | --- | --- |
        | col1 | col2 |
        | col1 | col2 |
```
