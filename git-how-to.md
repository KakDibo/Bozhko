1) создать ключ
ssh-keygen
ssh-keygen -t ed25519 -C "email"
2) Правый верхний угол - иконка - Settings - SSH and GPG keys -
- New SSH key 
Посмотреть ключ - cat~/.ssh/id_ed25519.pub
3) git clone <url>
на рабочий компьютер 
git clone git@github.com:username/repository.git

