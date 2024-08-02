# pypandoc-server

A server which uses markdown instead of html

## Why?

I made pypandoc-server to write less and do more. Since i last checked there were no markdown to html converting servers (that support pandoc markdown) out there.

## Where are you using it?

I am using this on my [Journal Project](https://github.com/WafiWadud/Journal) so that i don't have to write long and lengthy html files for my journal entries.

## How?

The server is written in python using the [pypandoc]() library. It works by finding all markdown files in the root directory and converting them to html and serving them when needed. (i.e https://journal-nala.onrender.com/Entry1.md returns the html version of Entry1.md)

## How to use?

> [!CAUTION]
> This is not a production server. DO NOT. USE. THIS. FOR. IMPORTANT. THINGS. IT. IS. NOT. SANITIZED. NOR. SAFE. AT. ALL. READ. THE. LICENSE. THERE. IS. NO. WARRANTY.

To install, run the following commands:

```bash
git clone https://github.com/WafiWadud/pypandoc-server.git
pip install fastapi uvicorn uvloop pypandoc_binary
cp pypandoc-server/pypandoc-server.py ./{your project}
```

To run, run the following command:

```bash
uvicorn pypandoc_server:app
```

### Alternatives

Psst. You wanna know some alternatives?

1. pug
2. handlebars.js
3. marko
4. nunjucks
5. hogun.js
6. haml
7. erb
