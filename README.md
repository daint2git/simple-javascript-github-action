# Simple javascript github action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

uses: actions/hello-world-javascript-action@v1.1
with:
  who-to-greet: 'Mona the Octocat'

## Release

```bash
yarn package
git commit -m "xxx"
git tag -a -m "My first action release" v1
git push --follow-tags


# delete git tag
git tag -d v1.0
```
