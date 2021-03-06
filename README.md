# My VNC setup

Runs [DWM](https://dwm.suckless.org).

## Colored Selection patch for DWM

Allows you to create VNC sessions with different colored selections to
distinguish between contexts.

For example, there are two examples for *Client* projects and *Hobby* projects.

-----
![Client](images/client_example.png "Client VNC")

-----
![Hobby](images/hobby_example.png "Hobby VNC")

-----
There can be multiple VNCs with different colors. For example, the image below
shows VNCs started with the following commands:


```console
% startvnc --name Client
% startvnc --name Hobby --port 2 --color 007733
% startvnc --name Development --port 1 --color 0022aa
```

![Stack of VNC sessions](images/example.png "Stack of VNC sessions")

