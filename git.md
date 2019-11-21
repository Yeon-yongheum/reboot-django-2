1. 특정 파일을 커밋 이력에서 삭제하고 싶다. 다만, 파일은 유지하고 싶을 때

예) .db.sqlite3가 이미 커밋이 되어버림

```bash
$ git rm --cashed db.sqlite3
```

위의 명령에를 작성하고 `.gitingore`에 `db.sqlite3`등록

2. unstage

```bash
$ git reset HEAD <file>
```

3.커밋 메시지 수정

```bash
$ git commit --amend
```

 