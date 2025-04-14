# llm-yt-transcript

`llm-yt-transcript` is a LLM plugin for YouTube transcripts as fragments. It leverages `yt-dlp` for downloading subtitles.

## Installation

```
llm install git+https://github.com/kj-9/llm-yt-transcript.git
```


## Usage

### Download Subtitles

Use the `download_subtitles` function to download subtitles for a YouTube video:
```python
llm -f hn:43615912 'summary with illustrative direct quotes'
```

## Development

To set up this plugin locally, first checkout the code. Then create a new virtual environment:

```
cd llm-hacker-news
uv sync
```

Now install the dependencies and test dependencies:

```
uv pip install -e '.[test]'
```
