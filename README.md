vscode-web-action
=================
### Notes
- use local settings
    - `git config core.filemode false`
    - `git config core.autocrlf false`

### Useful commands
- `docker container exec -it ${ container-id } bash`, and then run `.sh` files inside the bash
- `docker container exec -it ${ container-id } sh -c "echo 123"`
- `-it` is needed otherwise interactive programs like shell cannot remain running
