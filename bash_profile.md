```
#Flutter配置
export PUB_HOSTED_URL=https://pub.flutter-io.cn
export FLUTTER_STORAGE_BASE_URL=https://storage.flutter-io.cn 
export PATH=~/flutter/bin:$PATH

#系统
PATH=$PATH:/usr/bin:/bin

#Git常用命令配置
alias reignore='git rm -r --cache . && git add .'
alias whyignore='git check-ignore -v'
alias gl='git log'
alias glg='git log --stat'
alias glg='git log --graph'
alias gs='git status'
alias ga='git add'
alias gaall='git add .'
alias gcmsg='git commit -m'
alias gp='git push'
alias gpull='git pull'
alias gco='git checkout'
alias gcb='git checkout -b'
alias gd='git diff'
alias gf='git fetch'
alias gbd='git branch -d'
alias gbD='git branch -D'
alias gdob='git push --delete origin'
alias reignore='git rm -r --cached . && git add .'
alias whyignore='git check-ignore -v'
alias startApaServe='sudo apachectl start'
alias restartApaServe='sudo apachectl restart'
alias stopApaServe='sudo apachectl stop'

#打开iPhone模拟器
alias openIphone='open -a Simulator'

#打开安卓模拟器
alias openAndroid='/Applications/Android Studio.app/sdk/tools/emulator <Pixel_XL_API_28.avd> NHMU -netspeed full -netdelay none &'

[[ -s "$HOME/.rvm/scripts/rvm" ]] && source "$HOME/.rvm/scripts/rvm" # Load RVM into a shell session *as a function*

# >>> conda initialize >>>
# !! Contents within this block are managed by 'conda init' !!
__conda_setup="$('/Applications/anaconda3/bin/conda' 'shell.bash' 'hook' 2> /dev/null)"
if [ $? -eq 0 ]; then
    eval "$__conda_setup"
else
    if [ -f "/Applications/anaconda3/etc/profile.d/conda.sh" ]; then
        . "/Applications/anaconda3/etc/profile.d/conda.sh"
    else
        export PATH="/Applications/anaconda3/bin:$PATH"
    fi
fi
unset __conda_setup
# <<< conda initialize <<<

#逆向的相关配置
alias dump.py="~/frida-ios-dump/dump.py"

#theos配置环境变量
export THEOS=~/theos
export PATH=$THEOS/bin:$PATH

export THEOS_DEVICE_IP=127.0.0.1
export THEOS_DEVICE_PORT=10010




```