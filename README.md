# blazor-electron-demo

Demo code from ["Building Desktop Apps with Blazor"](https://jimbuck.io/building-desktop-apps-with-blazor-and-electron) from my blog [https://jimbuck.io](https://jimbuck.io).

Questions, comments, or complaints? Open an issue or hit me up on [Twitter](https://twitter.com/jimbuckio)!

## Run:

```sh
dotnet electronize start
```

## Publish:

### Windows:

```sh
dotnet electronize build /target win
```

### Linux:

```sh
dotnet electronize build /target linux
```

### OSX:

**Note:** Only works on OSX.

```sh
dotnet electronize build /target osx
```

## License:

MIT