<div align="center">

# asdf-opentelemetry-collector-contrib [![Build](https://github.com/thisisibrahimd/asdf-opentelemetry-collector-contrib/actions/workflows/build.yml/badge.svg)](https://github.com/thisisibrahimd/asdf-opentelemetry-collector-contrib/actions/workflows/build.yml) [![Lint](https://github.com/thisisibrahimd/asdf-opentelemetry-collector-contrib/actions/workflows/lint.yml/badge.svg)](https://github.com/thisisibrahimd/asdf-opentelemetry-collector-contrib/actions/workflows/lint.yml)

[opentelemetry-collector-contrib](https://github.com/open-telemetry/opentelemetry-collector-contrib) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add otelcol-contrib
# or
asdf plugin add otelcol-contrib https://github.com/thisisibrahimd/asdf-opentelemetry-collector-contrib.git
```

opentelemetry-collector-contrib:

```shell
# Show all installable versions
asdf list-all otelcol-contrib

# Install specific version
asdf install otelcol-contrib@latest

# Set a version globally (on your ~/.tool-versions file)
asdf global otelcol-contrib@latest

# Now opentelemetry-collector-contrib commands are available
otelcol-contrib --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/thisisibrahimd/asdf-opentelemetry-collector-contrib/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ibrahim Diallo](https://github.com/thisisibrahimd/)
