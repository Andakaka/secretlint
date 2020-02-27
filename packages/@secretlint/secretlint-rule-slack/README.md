# @secretlint/secretlint-rule-slack

A secretlint rule for slack.

## Install

Install with [npm](https://www.npmjs.com/):

    npm install @secretlint/secretlint-rule-slack

## Usage

Via `.secretlintrc.json`(Recommended)

```json
{
    "rules": [
        {
            "id": "@secretlint/secretlint-rule-slack"
        }
    ]
}
```

## Messages

### FOUND_SLACK_TOKEN
> found slack token: {{TOKEN}}

Disallow to write slack token as plain text.
You should encrypt it before using.

- [Types of tokens | Slack](https://api.slack.com/docs/token-types)

## Options

- `allows: string[]`

## Changelog

See [Releases page](https://github.com/secretlint/secretlint/releases).

## Running tests

Install devDependencies and Run `npm test`:

    npm test

## Contributing

Pull requests and stars are always welcome.

For bugs and feature requests, [please create an issue](https://github.com/secretlint/secretlint/issues).

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Author

- [github/azu](https://github.com/azu)
- [twitter/azu_re](https://twitter.com/azu_re)

## License

MIT © azu
