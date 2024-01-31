#GitOps

git init
git config --global user.email "xxxx@naver.com"
git config --global user.name "hhs"
git config credential.helper store  (~/.git_credentials)

git add .  (추적 시작 : staging storage에 위치)
git status
git diff
git config --list
git commit -am "add svc-nginx"  (commit storage에 위치)
git remote add origin https://github.com/xxx/gitops.git  (remote 저장소를 origin으로 등록)
git branch -M main  #-M move:push 하기위한 branch 등록
