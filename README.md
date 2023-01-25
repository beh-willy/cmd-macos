<p align="center"><a href="https://younision.com" target="_blank"><img src="https://www.dataquest.io/wp-content/uploads/2019/07/command-line-courses-dataquest-1000x520-1-1.gif" width="400" alt="Laravel Logo"></a></p>

# cmd-macos

Snipplet terminal command line for MacOS
<br><br>
**_<p>[Duplicate WeChat](https://younision.com)</p>_**
- Copy the code as below and paste inside the terminal, it will create a hidden file inside your Home folder, this script will need to re-execute if you reboot your operating system. To execute it use command ```bash .wechat.sh```
```bash
echo -e "nohup /Applications/WeChat.app/Contents/MacOS/WeChat> /dev/null 2>&1 &" >> wechat.sh && mv wechat.sh .wechat.sh
```
- After execute the first command if you wish to open the Dual WeChat, you need to execute the command as below
```bash
bash .wechat.sh
```
