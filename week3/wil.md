##이번 주에 배운 것

이번 주에는 commit의 버전을 확인하고 그것을 되돌리는 것을 배웠다.

git log로 commit의 버전을 확인할 수 있다.

commit의 버전은 고유한 id로 표기된다.

head는 현재 작업중인 위치를 말한다.

commit --amend 는 마지막 커밋을 대체하는 방법이다. 

git reset --"option" "commit Id"로 이전 커밋으로 되돌릴 수 있는데

option에 따라 돌아갈 commit Id의 이후 변경사항의 운명이 정해진다.

soft는 변경사항이 staging area로 mixed는 working directory로 hard는 변경사항이 제거된다.

reset과 다르게 revert는 이전 버전으로 돌아가는 것이 아닌 이전 버전을 새로운 commit으로 만든다.

