# hello-javascript-action

https://docs.github.com/ja/actions/creating-actions/creating-a-javascript-action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: akihisa1210/hello-javascript-action@v1.3
with:
  who-to-greet: "Mona the Octocat"
```
