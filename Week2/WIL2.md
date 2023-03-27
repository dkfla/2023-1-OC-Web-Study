```
1.
git add
작업 디렉토리 내에서 작업한 파일을 staging 영역으로 옮긴다.
git commit
staging 영역에 올라와 있는 작업 데이터를 로컬 저장소에 저장한다.
git push
로컬 저장소에 저장된 변경 내용을 원격 저장소로 보낸다.

git fetch
원격 저장소의 커밋들을 로컬 저장소로 가져온다. 자동으로 병합을 해주지 않기 때문에 확인을 한 후 직접 병합하는 과정을 거쳐야 한다.
git pull
원격 저장소의 정보를 가져오면서 자동으로 로컬 브랜치에 병합까지 수행해준다.

2.
Git: 파일의 변화를 추적
git add: Git이 추적한 변화들 중 다음 커밋에 포함시킬 변화들을 Staging Area에 쌓아둠
git commint: Staging Area에 쌓인 변화들을 논리적으로 엮어 이름을 붙여준 뒤, Local Repository에 넘겨줌
git push: Local Repository의 자료를 Remote Repository에 보냄
Github: 외부 저장소인 Remote Repository 서비스 중 하나
```