## Python
```bash
echo 'alias py=python' >> ~/.zshrc
```
### PyEnv
https://www.liquidweb.com/kb/how-to-install-pyenv-on-ubuntu-18-04/
```bash
git clone https://github.com/pyenv/pyenv.git ~/.pyenv

echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.zsrc
echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.zsrc
echo -e 'if command -v pyenv 1>/dev/null 2>&1; then\n eval "$(pyenv init -)"\nfi' >> ~/.zsrc

source ~/.zshrc
```

## Great applications

### nomacs Image Viewer
```bash
sudo apt install nomacs
```
  ![[Pasted image 20220512190513.png]]

```bash
gsettings set org.gnome.desktop.interface clock-show-seconds true
```
