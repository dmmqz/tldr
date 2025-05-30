# git add

> 변경된 파일을 색인에 추가합니다.
> 더 많은 정보: <https://git-scm.com/docs/git-add>.

- 파일을 색인에 추가:

`git add {{경로/대상/파일}}`

- 모든 파일 추가 (추적된 파일 및 추적되지 않은 파일):

`git add {{[-A|--all]}}`

- 현재 폴더의 모든 파일 추가:

`git add .`

- 이미 추적된 파일만 추가:

`git add {{[-u|--update]}}`

- 무시된 파일도 추가:

`git add {{[-f|--force]}}`

- 파일의 일부를 대화식으로 스테이징:

`git add {{[-p|--patch]}}`

- 지정된 파일의 일부를 대화식으로 스테이징:

`git add {{[-p|--patch]}} {{경로/대상/파일}}`

- 파일을 대화식으로 스테이징:

`git add {{[-i|--interactive]}}`
