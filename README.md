# Lab: Container Fun

## Goal
Get comfortable with the Docker CLI by using a lightweight Alpine container.

## Requirements
1.  **Pull**: Pull the `alpine` image.
2.  **Run**: Run it interactively (`-it`).
3.  **Explore**:
    -   Run `ls -la`.
    -   Check the OS version: `cat /etc/os-release`.
4.  **Modify**:
    -   Alpine doesn't have `curl` by default.
    -   Install it: `apk add curl`.
    -   Use it: `curl google.com`.
5.  **Clean**: Exit and remove the container.

## Deliverable
Take a screenshot of your terminal showing the output of the `curl` command inside the container.
