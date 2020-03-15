Installation
------------

Copy `tmux-share` to `/usr/local/bin`.

Usage
-----

When you are inside a tmux session, share it with another user by
running:

    tmux-share USER

You can run this command multiple times to share with multiple users.

If the user allows receiving terminal messages (`mesg(1)`) a message
how to connect to your session will be sent to him/her. Instructions
how to connect will be also printed to stdout.

To stop sharing your session, run:

    tmux-share -x

This revokes permissions for other users and disconnects them.
