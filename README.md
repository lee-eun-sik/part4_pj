# part4_pj
git clone https://github.com/salmonkiller2/simple_game.git # 깃 저장소 불러오기ㅊ
uv sync # 가상화 환경 셋팅
source .venv/Scripts/activate # 가상화 활성화
uv run simple-breakout 가상화 게임 실행
git init 깃 초기화
git status
echo "# repo_test" >> README.md
git add README.md
git branch -M main
git remote add origin https://github.com/lee-eun-sik/repo_test.git
git branch
git checkout -b main
rm -rf repo_test/.git
git add .
git config --global user.email "dldmstlr20419@naver.com"
git config --global user.name "lee-eun-sik"
git config --list
:wq하면 목록에서 빠져나옴
$ git commit -m "첫 커밋"