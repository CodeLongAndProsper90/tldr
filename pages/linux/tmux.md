# Tmux
> tmux is a terminal multiplexer. 
> It lets you switch easily between several programs in one terminal, detach them (they keep running in the background) and reattach them to a different terminal.

The default prefix is Ctrl-b.
When you see {prefix}, press Ctrl-b, release both keys and then hit the next sequence.

- Create a new window:

`{prefix}+c`

- Switch to window *x* (Starts from zero):

`{prefix}+{x}`

- Move to the next window:

`{prefix}+n`

- Move to the previous window:

`{prefix}+p`

- Close a window:

`{prefix}+x`

- Split a window vertically (|):

`{prefix}+%`

- Split a window horizontally (-):

`{prefix}-"`

- Move between windows:

`{prefix}-{arrow key}`

- Resize a window:
`{prefix}+Ctrl-{arrow}

- Name a session:

`tmux new -s{name}`

- Attach to a named session:

`tmux attach -t{name}`
