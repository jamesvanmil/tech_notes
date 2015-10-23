# Tmux

## New session

`$ tmux`

With name:

`$ tmux new -s name`

Rename:

`$ tmux rename-session -t 0 name`

## Connecting to a session

Find the session:

`$ tmux ls`

And attach:

`$ tmux attach -t name`

## Moving and manipulating panes (with command)

* Split vertical (-): `"`
* Split horizonal (|): `%`
* Move panes: `<arrow key>`
* Close pane: `C-d` or `$ exit`
* Create window: `c`
* Next window: `n`
* Previous window: `p`
* Zoom/full screen: `z`
* Rename: `,`

Detach with: `d`

## Other (with command)

* Enable scroll: `[`
