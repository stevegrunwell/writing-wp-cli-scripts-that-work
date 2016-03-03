###  tmux

Allows you to create multiple virtual consoles

```bash
$ tmux new -s my-long-running-process
```
<!-- .element: class="fragment" -->

```bash
# This is a new session that can be closed without stopping
$ wp my-plugin super-mega-import
$ [CTRL+B] d
```
<!-- .element: class="fragment" -->

```bash
$ tmux a -t my-long-running-process
```
<!-- .element: class="fragment" -->