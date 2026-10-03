1. alias.sh 자체를 HOME 경로에 저장 후 아래를 ~/.bashrc에 복사

```
[ -f "$HOME/alias.sh" ] && . "$HOME/alias.sh"
```


2. alias.sh의 내용을  ~/.bashrc에 복붙.

3. 그리고 현재 .bashrc 적용

```
source alias.sh 
```
