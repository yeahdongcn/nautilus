## vctl exec

Execute a command within a running container.

### Synopsis

Run the given command within the specified container.

```
vctl exec [OPTIONS] CONTAINER COMMAND [ARGUMENTS...]
```

### Examples

```
  # To execute 'top' in container myContainer in background (detached from current terminal).
  vctl exec --detach myContainer top

  # To get output from running 'date' command in myContainer.
  vctl exec myContainer date

  # To allocate a terminal for myContainer and send stdin to 'bash' in myContainer.
  vctl exec -it myContainer bash
```

### Options

```
  -d, --detach        Run the command in background
  -h, --help          Help for exec
  -i, --interactive   Keep STDIN open even if not attached
  -t, --tty           Allocate a terminal for the container
```

### SEE ALSO

* [vctl](vctl.md)	 - vctl - A CLI tool for the container engine powered by VMware Fusion

###### Auto generated by spf13/cobra on 14-Sep-2020