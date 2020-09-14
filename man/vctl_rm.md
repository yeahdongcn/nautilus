## vctl rm

Remove one or more containers.

### Synopsis

Delete all containers or delete by the given container(s).

```
vctl rm [OPTIONS] ([CONTAINER...]|--all)
```

### Options

```
  -a, --all      Delete all containers
  -f, --force    Force removal of container regardless of its status
  -h, --help     Help for rm
  -v, --volume   Remove anonymous volume used by the container
```

### SEE ALSO

* [vctl](vctl.md)	 - vctl - A CLI tool for the container engine powered by VMware Fusion

###### Auto generated by spf13/cobra on 14-Sep-2020