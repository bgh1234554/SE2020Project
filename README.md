# SE2020Project
소프트웨어개발실무 Git WorkFlow (2019071921 백지훈)

코드를 최종 배포하기 전, 개발하는 중에 있는 파일들을 올리는 브랜치. 배포가 가능할 경우, master 브랜치와 병합한다.

평소에는 개발할 때 사용하는 develop 브랜치를 주로 사용할 것이기 때문에, 기본 브랜치로 설정해둔다.

$ git push origin some-feature

(내 로컬 저장소의 some-feature branch를 중앙 원격 저장소로 올리는 명령)를 한 후,
Github 페이지에서 해당 some-feature branch에 대해 merge를 할 때 **중앙 원격 저장소의 ‘master’ branch가 아닌 default로 설정되어 있는 ‘develop’에 병합하도록**  설정하는 것이다.

깃을 클론한 뒤에 로컬 리포지터리와 연결시키는 법

$ git checkout -b develop origin/develop
