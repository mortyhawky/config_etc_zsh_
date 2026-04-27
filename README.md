### /etc/zsh/  Config Files

```bash
git init
echo "### /etc/zsh  Config Files" >> README.md
git add -Av
eza
git commit -m "$(date)"
git status
gh repo create config_etc_zsh_ --public --source=. --remote=origin
git push -u origin main
git status
```
