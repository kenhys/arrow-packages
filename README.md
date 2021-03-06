# README

Packages for Apache Arrow and related projects.

## Supported packages

  * Apache Arrow C++
  * Apache Arrow GLib (C API)
  * Apache Parquet C++
  * Parquet GLib (C API)

## Supported platforms

There are packages for the following platforms:

  * Debian GNU/Linux jessie
  * Ubuntu 16.04 LTS
  * Ubuntu 16.10
  * Ubuntu 17.04
  * CentOS 7

## Package repository

https://packages.groonga.org/ provides packages. You need to enable
the package repository before you install packages.

### Debian GNU/Linux

You add the following apt-lines to
`/etc/apt/sources.list.d/groonga.list`:

```text
deb https://packages.groonga.org/debian/ jessie main
deb-src https://packages.groonga.org/debian/ jessie main
```

Then you run the following command lines:

```text
% sudo apt install -y apt-transport-https
% sudo apt update
% sudo apt install -y --allow-unauthenticated groonga-keyring
% sudo apt update
```

### Ubuntu

```text
% sudo apt install -y software-properties-common
% sudo add-apt-repository -y ppa:groonga/ppa
% sudo apt update
```

### CentOS 7

```text
% sudo yum install -y https://packages.groonga.org/centos/groonga-release-1.3.0-1.noarch.rpm
```

## Apache Arrow C++

This section describes how to install
[Apache Arrow C++](https://github.com/apache/arrow/tree/master/cpp)
package.

### Debian GNU/Linux

```text
% sudo apt install -y libarrow-dev
```

### Ubuntu

```text
% sudo apt install -y libarrow-dev
```

### CentOS 7

```text
% sudo yum install -y --enablerepo=epel arrow-devel
```

## Apache Arrow GLib (C API)

This section describes how to install
[Apache Arrow GLib](https://github.com/apache/arrow/tree/master/c_glib)
package.

### Debian GNU/Linux

```text
% sudo apt install -y libarrow-glib-dev
```

### Ubuntu

```text
% sudo apt install -y libarrow-glib-dev
```

### CentOS 7

```text
% sudo yum install -y --enablerepo=epel arrow-glib-devel
```

## Apache Parquet C++

This section describes how to install
[Apache Parquet C++](https://github.com/apache/parquet-cpp) package.

### Debian GNU/Linux

```text
% sudo apt install -y libparquet-dev
```

### Ubuntu

```text
% sudo apt install -y libparquet-dev
```

### CentOS 7

```text
% sudo yum install -y --enablerepo=epel parquet-devel
```

## Parquet GLib

This section describes how to install
[Parquet GLib](https://github.com/red-data-tools/parquet-glib) package.

### Debian GNU/Linux

```text
% sudo apt install -y libparquet-glib-dev
```

### Ubuntu

```text
% sudo apt install -y libparquet-glib-dev
```

### CentOS 7

```text
% sudo yum install -y --enablerepo=epel parquet-glib-devel
```

## License

Apache-2.0

Copyright 2017 Kouhei Sutou \<kou@clear-code.com\>

See LICENSE and NOTICE for details.
