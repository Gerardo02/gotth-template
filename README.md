# GoTTH Stack template

The GoTTH stack is a powerful development stack designed specifically for solo gophers. It provides an efficient and enjoyable development experience for building web applications. The stack combines the following technologies:

- **Go** - A statically-typed and compiled programming language known for its simplicity, efficiency, and scalability. [Official Documentation](https://golang.org/doc/)
- **Templ** - An HTML templating language for Go that has great developer tooling. [Official Documentation](https://templ.guide/)
- **Tailwind CSS** - A utility-first CSS framework that enables rapid UI development with pre-designed utility classes. [Official Documentation](https://tailwindcss.com/docs/)
- **HTMX** - A lightweight JavaScript library for seamless and interactive web applications. [Official Documentation](https://htmx.org/docs/)

## Getting started

### Prerequisites

GoTTH requires: 
- [Go](https://go.dev/) version [1.23](https://go.dev/doc/devel/release#go1.23.0) or above.
- GNU [make](https://www.gnu.org/software/make/).

### Required CLI tools

Install [templ](https://templ.guide/quick-start/installation/)
```bash
go install github.com/a-h/templ/cmd/templ@latest
```

Install [air](https://github.com/air-verse/air)
```bash
go install github.com/air-verse/air@latest
```

Standalone [tailwind](https://github.com/tailwindlabs/tailwindcss/releases/tag/v4.1.11) CLI
<br />
or
```bash
npm install tailwindcss @tailwindcss/cli
```

## Installation
Clone the repo
```bash
git clone https://github.com/Gerardo02/gotth-template.git
```
```bash
make install
```

Consider changing the HTMX tag in the base component from a CDN to a local file.
<br />
Enjoy your Javascript free experience
