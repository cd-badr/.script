# .script

## installation

```bash
cd ~/
git clone https://github.com/ie-orphane/.script.git
```

## for windows

```bash
echo "export PATH=\"~/.script/commands:\$PATH\"" >> ~/.bash_profile ~/.bashrc
```

## for linux

```bash
echo "export PATH=\"~/.script/commands:\$PATH\"" >>  ~/.bashrc

sudo chmod +x ~/.script/commands/discord
```

## discord

- `discord new` create new discord.py project
- `discord install` install a dependency and add it to requirements.txt
- `discord run` run the bot
- `discord init` copy the .env.example to .env if not existed
- `discors add`

  -c|--cog create new cog/slash command

  -t|--task create new task

  -m|--model create new database model
