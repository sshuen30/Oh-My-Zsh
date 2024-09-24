## Install neofetch and add the text 'neofetch' at the end of ~/.zshrc file
```bash
sudo apt install neofetch
```

## Install Zsh
```bash
sudo apt install zsh
```

## Install Oh-My-Zsh
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

- Install Zsh auto suggestions
```bash
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

- Install Zsh syntax highlighter
```bash
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

- Edit ~/.zshrc and update the following:
```bash
nano ~/.zshrc
```
![Screenshot 2024-02-24 002342](https://github.com/sshuen30/Oh-My-Zsh/assets/40738215/997ff4cc-c9de-47ae-8b2e-bd59f30f5181)

![Screenshot 2024-02-24 002612](https://github.com/sshuen30/Oh-My-Zsh/assets/40738215/32f6cfcd-07ee-4a78-916d-cc3bf3374131)

```bash
plugins=(
 git
 zsh-autosuggestions
 zsh-syntax-highlighting
)
```

- Command to apply changes without exiting shell
```bash
source ~/.zshrc
```

- Check what is the current shell
```bash
echo $SHELL
```

- Change bash shell to Zsh shell
```bash
chsh -s /bin/zsh
```

