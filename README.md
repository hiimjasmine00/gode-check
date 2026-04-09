# gode-check
A CLI that checks the hashes of Geode mods, comparing GitHub releases with workflow artifacts.\
(Originally written in JavaScript by [Prevter](https://github.com/Prevter), rewritten in Rust by [hiimjasmine00](https://github.com/hiimjasmine00).)

## Usage
```
gode-check <release link> [option]
```

### Options
Option | Alias | Argument | Description
-------|-------|----------|------------
--branch | -b | Branch name | Specify a branch to get the artifacts from instead of the release commit.
--commit | -c | Commit hash | Specify a commit to get the artifacts from instead of the release commit.
```

Optionally, you can set the `GODE_CHECK_GITHUB_TOKEN` environment variable to fetch GitHub requests authenticated for a higher rate limit.

## License
This project is licensed under the [MIT License](./LICENSE).
