## Prerequisites

- Install texlive

```
sudo apt install texlive-full
```

- Install Overleaf command line (`ols`)

```sh
pip3 install overleaf-sync
```

- Create `tkhar-slide` directory, and sync project from overleaf.

```sh
mkdir tkhar-slide
ols login
ols -r
```

- Install vscode

```
wget -qO- https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > packages.microsoft.gpg
sudo install -o root -g root -m 644 packages.microsoft.gpg /etc/apt/trusted.gpg.d/
sudo sh -c 'echo "deb [arch=amd64 signed-by=/etc/apt/trusted.gpg.d/packages.microsoft.gpg] https://packages.microsoft.com/repos/vscode stable main" > /etc/apt/sources.list.d/vscode.list'
sudo apt-get install apt-transport-https
sudo apt-get update
sudo apt-get install code # or code-insiders
```

- Install Latex Workshop

```
ext install James-Yu.latex-workshop
```

## Author

[**khoidd**](), [**thucth**]()