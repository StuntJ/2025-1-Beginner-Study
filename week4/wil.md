##이번 주 배운 것

이번 주에는 실습 없이 git을 통해 어떻게 개발이 진행되는지 전체적인 흐름을 알아보았다.

git flow 와 github flow에 대하여 배웠다.

git flow는 5가지 브랜치로 구성이 되며, main, develop, feature, release, hotfix branch가 있다.

main이 최종 결과물에 적용이 되는 branch, develop이 테스트 하는 공간이며, 나머지 3개는 서브 브랜치이다.

hotfix는 main에서 긴급하게 고쳐야할 버그가 발견되었을 때 쓰는 브랜치이다. 버그를 고치고, main과 develop으로 merge한다.

feature은 추가적인 개발을 할 때 쓰인다. 다 만든 다음 test server와 비슷한 develop으로 merge 한다.

release는 develop에서 main으로 수정사항을 보내기 전 최종 수정자 역할을 한다.

release에서 수정한 내용은 develop과 main으로 보내져야 한다.

다음은 github flow이다. github flow는 main과 feature로 구성이 된다.

develop 공간 없이 그냥 feature에서 작업한 후 바로 main으로 병합하기 때문에 신중하게 merge해야 한다.

장점은 수정되야할 사항이 아주 빠르게 수정된다는 것이다.

이렇게 깃의 흐름에 대해서는 거진 이해를 한 것 같다. 개발하러 가보자잇!