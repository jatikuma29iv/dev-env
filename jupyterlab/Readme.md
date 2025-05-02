# Jupyter Lab

## Overview
Creates invironment to run Jupyter Lab

## One click start
```bash
docker build -f https://raw.githubusercontent.com/jatikuma29iv/dev-env/refs/heads/main/jupyterlab/Dockerfile -t jupyterlab .
docker run --rm -v $(pwd):/app -p 8888:8888 --name jupyterlab jupyterlab

# output
[I 2025-05-02 07:44:42.378 ServerApp] jupyter_server_terminals | extension was successfully linked.
[I 2025-05-02 07:44:42.380 ServerApp] jupyterlab | extension was successfully linked.
[I 2025-05-02 07:44:42.382 ServerApp] Writing Jupyter server cookie secret to /root/.local/share/jupyter/runtime/jupyter_cookie_secret
[I 2025-05-02 07:44:42.664 ServerApp] notebook_shim | extension was successfully linked.
[I 2025-05-02 07:44:42.674 ServerApp] notebook_shim | extension was successfully loaded.
[I 2025-05-02 07:44:42.675 ServerApp] jupyter_lsp | extension was successfully loaded.
[I 2025-05-02 07:44:42.676 ServerApp] jupyter_server_terminals | extension was successfully loaded.
[I 2025-05-02 07:44:42.676 LabApp] JupyterLab extension loaded from /usr/local/lib/python3.13/site-packages/jupyterlab
[I 2025-05-02 07:44:42.676 LabApp] JupyterLab application directory is /usr/local/share/jupyter/lab
[I 2025-05-02 07:44:42.677 LabApp] Extension Manager is 'pypi'.
[I 2025-05-02 07:44:42.708 ServerApp] jupyterlab | extension was successfully loaded.
[I 2025-05-02 07:44:42.709 ServerApp] Serving notebooks from local directory: /User/you/app
[I 2025-05-02 07:44:42.709 ServerApp] Jupyter Server 2.15.0 is running at:
[I 2025-05-02 07:44:42.709 ServerApp] http://7917aef9d12e:8888/lab?token=da08e7fe1fcb62fca99c875185b7823ac2296064d45edc2f
[I 2025-05-02 07:44:42.709 ServerApp]     http://127.0.0.1:8888/lab?token=da08e7fe1fcb62fca99c875185b7823ac2296064d45edc2f
[I 2025-05-02 07:44:42.709 ServerApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
[W 2025-05-02 07:44:42.713 ServerApp] No web browser found: Error('could not locate runnable browser').
[C 2025-05-02 07:44:42.714 ServerApp]

    To access the server, open this file in a browser:
        file:///root/.local/share/jupyter/runtime/jpserver-1-open.html
    Or copy and paste one of these URLs:
        http://7917aef9d12e:8888/lab?token=da08e7fe1fcb62fca99c875185b7823ac2296064d45edc2f
        http://127.0.0.1:8888/lab?token=da08e7fe1fcb62fca99c875185b7823ac2296064d45edc2f
[I 2025-05-02 07:44:42.720 ServerApp] Skipped non-installed server(s): bash-language-server, dockerfile-language-server-nodejs, javascript-typescript-langserver, jedi-language-server, julia-language-serve
r, pyright, python-language-server, python-lsp-server, r-languageserver, sql-language-server, texlab, typescript-language-server, unified-language-server, vscode-css-languageserver-bin, vscode-html-langua
geserver-bin, vscode-json-languageserver-bin, yaml-language-server
```

open URL in browser:
http://127.0.0.1:8888/lab?token=da08e7fe1fcb62fca99c875185b7823ac2296064d45edc2f

