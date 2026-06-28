# Premium Calculator Collection

A small collection of themed calculator interfaces built as standalone HTML files. Each calculator demonstrates a different tech-stack style while keeping the project easy to open, inspect, and share.

## Calculators

| File | Calculator | Stack Theme |
| --- | --- | --- |
| `index.html` | Scientific calculator | HTML + CSS + JavaScript |
| `rust-wasm.html` | Programmer calculator | Rust + WebAssembly |
| `go-rest.html` | Scientific calculator | Go + REST API |
| `ruby-sinatra.html` | Scientific calculator | Ruby + Sinatra |
| `python-streamlit.html` | Scientific calculator | Python + Streamlit |

## Features

- Basic arithmetic: addition, subtraction, multiplication, and division
- Scientific functions: `sin`, `cos`, `tan`, `log`, `ln`, square root, powers, parentheses, `pi`, and `e`
- DEG/RAD angle mode on the scientific calculators
- Programmer calculator with decimal, binary, hexadecimal, and octal display
- Bitwise operations in the programmer calculator
- Keyboard support for common calculator actions
- Responsive layouts for desktop and mobile screens
- Distinct visual themes for each stack-inspired calculator

## How To Run

No build step is required. Open any calculator file directly in your browser:

```text
index.html
rust-wasm.html
go-rest.html
ruby-sinatra.html
python-streamlit.html
```

You can also run a simple local server from the project folder:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Project Structure

```text
premium-calculator/
├── index.html
├── rust-wasm.html
├── go-rest.html
├── ruby-sinatra.html
├── python-streamlit.html
├── README.md
└── supporting notes/docs
```

## Notes

The stack-specific pages are visual simulations of those ecosystems. They are intentionally self-contained HTML/CSS/JavaScript files so the project can be viewed without installing Rust, Go, Ruby, Python, Streamlit, or Sinatra.

## License

Use this project for learning, experimentation, and portfolio work.
