# part4_pj
git clone https://github.com/lee-eun-sik/part4_pj.git # 깃 저장소 불러오기ㅊ
git init 깃 초기화
git status
echo "# part4_pj" >> README.md
git add README.md
git branch -M main
git remote add origin https://github.com/lee-eun-sik/part4_pj.git
git branch
git checkout -b main
git add .
git config --global user.email "자기 이메일 쓸것!"
git config --global user.name "자기 이름 쓸것!"
git config --list
:wq하면 목록에서 빠져나옴
$ git commit -m "첫 커밋"
cd part4_pj
git add .
git commit -m "서브모듈 내부 수정"