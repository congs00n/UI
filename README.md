# UI
$ echo "# 새 레포지토리 주소" >> README.md
$ git init
> ' 업로드할 폴더 주소 '안의 기존 깃 저장소를 다시 초기화했습니다
$ git status
$ git add README.md
$ git commit -m "first commit"
$ git remote add origin '새 레포지토리 주소'
$ git push -u origin master
