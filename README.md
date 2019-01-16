# memory-lane

A script for downloading photos from Slack

- [Usage](#usage)
- [Configuration](#configuration)

## Usage

First, run `bundle install` to install dependencies. Then:

```bash
./bin/memory-lane
```

## Configuration

First, you must create a `config.yml` file that includes the following values:

```yaml
slack:
  api_token: <YOUR TOKEN HERE>
  channels:
    - "#foo"
    - "#bar"
    - "#baz"
```
