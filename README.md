# Vitejs-docker-setup

Using Vitejs with docker setup and commands in a Makefile

## Install
1. Clone this repository

2. Create a new vite project o add to an existing project

```bash
npm create vite@latest
```

3. Change var values that you need and copy the `env.example` to a `.env file` with

```bash
cp env-example .env
```

4. Use Makefile commands to interact with project

```bash
# This will install necessary packages and run dev script putting project in http://localhost:5173 port
make first
```

## Help

See all commands with
```bash
make help
```

## Links

Original versions used as base source and additional setup to generate Library with Vite

- [Vite setup to build a Library](https://www.freecodecamp.org/news/build-a-css-library-with-vitejs/)
- [Setup docker with Vite](https://dev.to/ysmnikhil/how-to-build-with-react-or-vue-with-vite-and-docker-1a3l)
