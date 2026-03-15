# {project-name}

{one-line description}

All logic lives in a single file (`main.{lang}`).

> **1fileagent rule**: LLM API を使った agent loop を 1 日 1 つ実装する。技術スタックは自由だが、エージェントのコードは `main.{lang}` 1 ファイルにまとめる。テスト・ビルド設定など補助ファイルは別で OK。

## Features

- {feature 1}
- {feature 2}
- {feature 3}

## Requirements

- {runtime} >= {version}
- An OpenAI-compatible API key

## Setup

```bash
cp .env.example .env
# Edit .env with your API key and preferences
```

## Usage

```bash
{run command}
```

### CLI options

```
--model <name>        Model name (default: gpt-4o-mini / $OPENAI_MODEL)
--api-key <key>       API key (default: $OPENAI_API_KEY)
--base-url <url>      Base URL (default: $OPENAI_BASE_URL)
{additional options}
```

## Testing

```bash
{test command}
```

## Project Structure

```
main.{lang}      All types, constants, and logic in a single file
{other files}
```

## License

MIT
