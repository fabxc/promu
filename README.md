# Prometheus Utility Tool

## Usage

```
promu is the utility tool for Prometheus projects

Usage:
  promu [flags]
  promu [command]

Available Commands:
  build       Build a Go project
  crossbuild  Crossbuild a Go project using Golang builder Docker images
  info        Print info about current project and exit
  release     Upload tarballs to the Github release
  tarball     Create a tarball from the builded Go project
  version     Print the version and exit

Flags:
      --config string   Config file (default is ./.promu.yml)
  -v, --verbose         Verbose output
      --viper           Use Viper for configuration (default true)

Use "promu [command] --help" for more information about a command.
```

## `.promu.yml` config file

See documentation example [here](doc/examples/.promu.yml)

## More information

  * All of the core developers are accessible via the [Prometheus Developers Mailinglist](https://groups.google.com/forum/?fromgroups#!forum/prometheus-developers) and the `#prometheus` channel on `irc.freenode.net`.

## Contributing

Refer to [CONTRIBUTING.md](CONTRIBUTING.md)

## License

Apache License 2.0, see [LICENSE](LICENSE).