# git_tutorial

## local workflow

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
