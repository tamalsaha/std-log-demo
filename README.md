# std-log-demo

## Demo Projects

- https://github.com/tamalsaha/std-log-demo
- https://github.com/tamalsaha/glog-demo
- https://github.com/tamalsaha/kube-log-demo
- https://github.com/tamalsaha/ac-log-demo

```console
$ go install -v

$ std-log-demo check -h
Check restic backup

Usage:
  stash check [flags]

Flags:
  -h, --help   help for check

Global Flags:
      --analytics   Send analytical events to Google Analytics (default true)

$ std-log-demo check
2018/01/08 18:04:40 FLAG: --analytics="true"
2018/01/08 18:04:40 FLAG: --help="false"
log.Println_____
2018/01/08 18:04:40 node.Name
```
