# To run
copy this repo to linux os:

```
mkdir ~/.config
cd ~/.config
git clone https://github.com/gongysh2004/clash.git
```

copy your config file:
```
cp your_config_file clash/config.yaml
```

start the clash:
```
tmux new-session -d -s "clash" ~/.config/clash/clash.linux -f ~/.config/clash/config.yaml
```
after that, you can attach the session:
```
tmux a -t clash
```

# To access the dashboard
http://{your-ip}:9090/ui/
