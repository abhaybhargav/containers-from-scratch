## Container from scratch

> written in Go

### Steps to run

> must be run as `root` or with `sudo`

#### Step 1

Create a ubuntu based fs at `/root/container-fs` for the filesystem mount

#### Step 2

```bash

go run main.go run /bin/bash

```

> puts you into a shell on the "container" with its own namespace, PID and UTS separation
