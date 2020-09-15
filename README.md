# @thanksd/hello-action

Simple GitHub Action package for learning

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: actions/hello-action@v1.1
with:
  who-to-greet: 'Brian' 
```
