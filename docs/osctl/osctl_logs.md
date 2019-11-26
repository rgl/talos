<!-- markdownlint-disable -->
## osctl logs

Retrieve logs for a process or container

### Synopsis

Retrieve logs for a process or container

```
osctl logs <id> [flags]
```

### Options

```
  -h, --help         help for logs
  -k, --kubernetes   use the k8s.io containerd namespace
  -c, --use-cri      use the CRI driver
```

### Options inherited from parent commands

```
      --talosconfig string   The path to the Talos configuration file (default "/root/.talos/config")
  -t, --target strings       target the specificed node
```

### SEE ALSO

* [osctl](osctl.md)	 - A CLI for out-of-band management of Kubernetes nodes created by Talos

###### Auto generated by spf13/cobra on 13-Nov-2019