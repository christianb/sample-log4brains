# Sample Log4Brains

This is a sample repository how to use [Log4Brains](https://github.com/thomvaill/log4brains).

## Starting the Server

You can run the docker container like
```bash
docker run --rm -ti -v $(pwd):/workdir -p 4004:4004 thomvaill/log4brains help
```

Starting the server
```bash
docker run --rm -ti -v $(pwd):/workdir -p 4004:4004 thomvaill/log4brains preview
```

The server will then become locally available at [http://localhost:4004](http://localhost:4004)

In preview mode, the Hot Reload feature is enabled: any change you make to a markdown file is applied live in the UI.

## More information

- [Log4brains documentation](https://github.com/thomvaill/log4brains/tree/master#readme)
- [What is an ADR and why should you use them](https://github.com/thomvaill/log4brains/tree/master#-what-is-an-adr-and-why-should-you-use-them)
- [ADR GitHub organization](https://adr.github.io/)
