# git_tutorial

## main branch workflow

```
1. remote repo 복제
git clone https://github.com/lina-dna/git_tutorial.git
```

```
1-1. 기존에 repo에 존재할 경우 git pull을 통해 local repo 업데이트
git pull
(이때, remote repo와 local repo 간의 충돌 사항이 발생할 경우 충돌사항 메뉴얼로 수정 후 2번으로 넘어감)
```

```
2. 파일 변경분 저장 후 staging에 반영(README.md 파일 변경했을 경우)
git add README.md
```

```
3. 파일 변경분 local repo에 반영하기 위해 commit(커밋 메시지로 작업 내용 노트)
git commit -m "modify readme"
```

```
4. remote repo에 push하여 작업사항 반영
git push
```

## other branch workflow
```
1. main branch로부터 branch 생성(여기서의 branch 이름은 dev)
git checkout -b dev
```

```
2. 생성된 local repo의 branch를 remote repo에 반영
git push --set-upstream origin dev
```

```
3. git add, commit, push를 통한 other branch 작업분 반영
```

```
4. other branch의 내용을 합치고자 하는 branch로 이동, 이동 후 합치려는 branch 표기
git checkout master
git merge dev
```
