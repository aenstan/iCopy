[<img src="https://f002.backblazeb2.com/file/jsuforum-upload/optimized/1X/cff2835c1652bb57a18aac42a3eee34b51cd9b89_2_1380x386.gif" width="50%" alt="jclone">](https://bbs.jsu.net/c/official-project/icopy/6)  

[![iCopy Telegram-Bot](https://img.shields.io/badge/iCopy-Telegram%20BOT-red)](https://bbs.jsu.net/c/official-project/icopy/6)
[![Programming Language](https://img.shields.io/badge/Python-3.6%20%2B-infomation)](https://bbs.jsu.net/c/official-project/icopy/6)
[![Version](https://img.shields.io/badge/Version-0.1.3--beta.2-ff69b4)](https://bbs.jsu.net/c/official-project/icopy/6)
[![License](https://img.shields.io/github/license/fxxkrlab/iCopy)](https://bbs.jsu.net/c/official-project/icopy/6)  

[iCopy Forum](https://bbs.jsu.net/c/official-project/icopy/6) |
[TELEGRAM GROUP](https://t.me/sharegdrive) |
[CHANGELOG](CHANGELOG.md)  
 
**Send commands to [Telegram](http://telegram.org) BOT for get a ####_convience way to control_ [gclone](https://github.com/donwa/gclone) resources copy missions.**  

## Install  
1.Python 3.6+ is Required  
2.Pre-install screen  
3.Pre-install and Configured [gclone](https://github.com/donwa/gclone) is Reqired  
  For Linux directly use this command  
  `bash <(wget -qO- https://git.io/gclone.sh)`  
4.`git clone https://github.com/fxxkrlab/iCopy.git && cd iCopy`  
5.`python3 -m venv .`  
6.`. ./bin/activate`  
7.`pip3 install -r requirements.txt`  
8.`cp settings.py.example settings.py`  
9.Edit settings.py   

* TOKEN : Bot API Token generated by BotFather  
* ENABLED_USERS : Your telegram user id. Only enabled users can use this bot.  
* Remote : Your gclone config name.like "gc"  
* Pre_Dst_id : Pre-Assigned Google Drive Destination Folder ID for quick mode  
* sa_path : The directory where your "service_accounts.json" is. End without slash "/".  
            NOTICE : "~" is not supported in the path.  

#### Start iCopy BOT :   
##### Start :  
`python3 -u iCopy.py`  

##### Start via screen :  
``screen -dmS iCopy `which python3` -u iCopy.py``  

#### 本项初愿本意通过学习 方便群友自定义转存机器人以及快捷命令  
#### 由于需求扩大 决定转为一个成品项目 慢慢完善  
#### 由于目前出于持续更新和半成品状态 给大家造成了麻烦 真的很抱歉
#### 若有网上的朋友不明白的欢迎加TG群 [Google Drive 资源互通](https://t.me/sharegdrive)  