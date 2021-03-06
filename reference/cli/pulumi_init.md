## pulumi init

Initialize a new Pulumi repository

### Synopsis


Initialize a new Pulumi repository

```
pulumi init [flags]
```

### Options

```
  -h, --help           help for init
      --name string    Override the repository name; default is taken from current Git repository or current working directory
      --owner string   Override the repository owner; default is taken from current Git repository or username
```

### Options inherited from parent commands

```
  -C, --cwd string                   Run pulumi as if it had been started in another directory
      --disable-integrity-checking   Disable integrity checking of checkpoint files
  -e, --emoji                        Enable emojis in the output (default true)
      --logflow                      Flow log settings to child processes (like plugins)
      --logtostderr                  Log to stderr instead of to files
      --profiling string             Emit CPU and memory profiles and an execution trace to '[filename].[pid].{cpu,mem,trace}', respectively
      --tracing string               Emit tracing to a Zipkin-compatible tracing endpoint
  -v, --verbose int                  Enable verbose logging (e.g., v=3); anything >3 is very verbose
```

### SEE ALSO
* [pulumi](pulumi.md)	 - 

###### Auto generated by spf13/cobra on 19-May-2018
