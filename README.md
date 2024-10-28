# Textpod

Local, web-based notetaking app inspired by "One Big Text File" idea. Short demo:

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/VAqJJxaJNVM?si=BZZMxbN9r_SFXw74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

- Single page with all notes and a simple entry form (Markdown)
- All notes are stored in a single `notes.md` file
- Search/filtering when you start typing with `/`
- Start a link with `+` and Textpod will save a local single-page copy
- File and image attachments

## Installation

```
cargo install textpod
```

In order to download webpages, you need to have `monolith` installed.

```
cargo install monolith
```

## Usage

Run `textpod` in any directory. It will create a `notes.md` file if it doesn't exist. It will create `attachments` directory for file and image attachments.
Webpages are saved in `attachments/webpages`. You can specify the port with `-p` flag, e.g. `textpod -p 8080`.

## Contributing

Feel free to open issues and pull requests. I want to keep the code very simple and accessible to beginners. The goal is not to create another feature-rich notetaking app, but to keep it simple and fast.
A "one big text file" idea is very powerful and I just want to make it slightly enhanced.
