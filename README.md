# gnome-shell-extension-containers

**Containers** is a gnome-shell extension to manage linux container, run by [libpod](https://github.com/containers/libpod) and https://podman.io

Supported actions:
- start a stopped container
- stop a container
- remove a container
- view and copy most of the `inspect` info

# Install using your browser 

See the [gnome extensions page](https://extensions.gnome.org/extension/1500/containers/)  

# Install from source

First pick the right branch by the `gnome-shell-X.XX` version: 

| branch | gnome-shell version |
| --- | --- |
| master | 3.36.1 |
| 3.36   | 3.36.4 |
| 3.34.2 | 3.34.2 |
| 3.28.3 | 3.28.3 |

Clone, Pack, and Install

```console
$ git clone https://github.com/rgolangh/gnome-shell-extension-containers
$ make all
```

Or using 'Tweaks' -> Extensions -> toggle 'Containers':

<p>
  <img src="screenshot.png" width="350" title="gnome-shell-extension-containers">
</p>
