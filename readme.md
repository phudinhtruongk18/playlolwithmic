# Please check first with (chat gpt) before do anything with you terminal

The solution from 

https://www.reddit.com/r/macgaming/comments/10d4kyy/fix_for_league_of_legends_mic/

Thank you

```sh
cat << 'EOF' > ~/Desktop/lolscript.command
#!/bin/bash
cd '/Applications/League of Legends.app/Contents/LoL/'
./LeagueClient.app/Contents/MacOS/LeagueClient
EOF

chmod u+x ~/Desktop/lolscript.command
```
