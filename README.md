# pypandoc-server

A server which uses markdown instead of html

## Why?

I made pypandoc-server to write less and do more. Since i last checked there were no markdown to html converting servers (that support pandoc markdown) out there.

### Where are you using it?

I am using this on my [Journal Project](https://github.com/WafiWadud/Journal) so that i don't have to write long and lengthy html files for my journal entries.

### How?

The server is written in python using the [pypandoc](https://pypandoc.readthedocs.io/en/stable/) library. It works by finding all markdown files in the root directory and converting them to html and serving them when needed. (i.e https://journal-nala.onrender.com/Entry1.md returns the html version of Entry1.md)
