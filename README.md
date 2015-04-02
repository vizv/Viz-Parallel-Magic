#VPM - Viz Parallel Magic

A X11 Dockerization Magic

## Usage

### build

Build a parallel magic image

Example (build a ubuntu:14.04 image):
```
$ vpm build ubuntu:14.04
```

### run

Run a pre-build container
Example (run a ubuntu:14.04 container):
```
$ vpm run ubuntu:14.04
```

Example (run a ubuntu:14.04 container with name test):
```
$ vpm run ubuntu:14.04 test
```

### list

List VPM images/containers

Example (list images):
```
$ vpm list i
```

Example (list containers):
```
$ vpm list c
```

### kill

Kill a container

Example (kill container with ID ac82066dffa6):
```
$ vpm kill ac82066dffa6
```

Example (kill container with name test):
```
$ vpm kill test
```

### resume

Resume a container and attach to it

Example (resume container with ID ac82066dffa6):
```
$ vpm resume ac82066dffa6
```

Example (resume container with name test):
```
$ vpm resume test
```

### destroy

Permanently destroy a container

Example (destroy container with ID ac82066dffa6):
```
$ vpm destroy ac82066dffa6
```

Example (destroy container with name test):
```
$ vpm destroy test
```

---

#VPM - Viz Parallel Magic

一个在 Docker 中跑 X11 应用的黑魔法

## 用法

### build

构建一个 VPM 的 Docker 镜像

例子 (构建一个 ubuntu:14.04 镜像):
```
$ vpm build ubuntu:14.04
```

### run

启动一个新的 VPM 容器
例子 (启动一个 ubuntu:14.04 容器):
```
$ vpm run ubuntu:14.04
```

例子 (启动一个 ubuntu:14.04 容器，并取名 test):
```
$ vpm run ubuntu:14.04 test
```

### list

列出 VPM 的镜像/容器

例子 (列出镜像):
```
$ vpm list i
```

例子 (列出容器):
```
$ vpm list c
```

### kill

强行终止一个容器

例子 (终止一个 ID 为 ac82066dffa6 的容器):
```
$ vpm kill ac82066dffa6
```

例子 (终止一个名字为 test 的容器):
```
$ vpm kill test
```

### resume

恢复一个容器

例子 (恢复一个 ID 为 ac82066dffa6 的容器):
```
$ vpm resume ac82066dffa6
```

例子 (恢复一个名字为 test 的容器):
```
$ vpm resume test
```

### destroy

永久销毁一个容器

例子 (销毁一个 ID 为 ac82066dffa6 的容器):
```
$ vpm destroy ac82066dffa6
```

例子 (销毁一个名字为 test 的容器):
```
$ vpm destroy test
```
