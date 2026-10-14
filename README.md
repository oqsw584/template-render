# template-render

A small template renderer supporting variables, loops and conditionals.

## Why

I kept rewriting the same thirty lines in every project, so I pulled them out.

## Install

```bash
pip install template-render
```

## Usage

```python
from template_render import templateRender

result = templateRender("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
