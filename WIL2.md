## 1주차 내용 복습

허니콤보를 리소스라고 했을 때 내가 원하는 리소스를 얻을 수 있는 주소가 교촌치킨신촌점이라고 볼 수 있는 URL이다.
원래는 복잡한 IP주소를 통해 리소스에 접근해야 하지만 
HTML, CSS, JS를 재료 삼아 브라우저가 그림을 그려준다 (랜더링)
HTML: 자료 (뼈대)
CSS: UI(살과 옷)
JavaScript: 제어

## 2주차 내용 복습
Working Directory는 "작업 공간"으로 내가 코드를 짜고 있는 공간이다. 
우리가 만든 변화들을 모아둘 수 있는 공간을 Staging Area라고 부른다.

-> add, commit,push 명령어

git add 명령어를 통해 working directory에 있는 변화들 중 다음 커밋에 포함시키 변화를 Staging Area에 쌓아둘 수 있다.
git commit 명령어를 통해 staging area에 있는 변화를 엮어 Local Repository에 commit할 수 있다.
깃허브는 깃 + Hub로 일종의 저장소이며 단지 Remote Repository를 제공해주는 서버중 하나이다.
push 명령어를 통해서 내가 commit한 코드를 친구와 공유할 수 있다.

- >Fetch와 Pull의 차이
- 둘다 결국 원격저장소의 내용을 가져오는데 사용됩니다.
fetch는 가져온 변경내용을 로컬에 영향을 미치지 않으며, 병합하기전에 확인하는 용도로 사용하는 것이 좋습니다.
pull은 가져온 변경내용을 로컬에 병합합니다. 하지만 로컬에서 작업하다가 변경된 내용을 pull할 경우 충돌이 일어날 수 있습니다.
왠만해선 fetch후 pull을 로컬이 깨끗한 상태에서 사용하는게 좋습니다. fetch와 pull을 적절하게 사용합시다.

