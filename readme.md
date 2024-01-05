이 문서는 2024년 1월 2일에 작성되었습니다.
git 명령어
Commit & Push
1. commit: 로컬 저장소에 코드 변경 이력을 남기는 것
2. push: 원격 저장소에 코드 변경을 업로드 함
    git push <저장소명> <브랜치명>
    ex. git push origin main
    git push -u <저장소명> <브랜치명>으로 이후 git push만 해도 됨
3. remote: 원격 저장소명을 반환

Pull & Fetch
원격 저장소에서 로컬 저장소로 소스를 가져옴
pull과 fetch의 차이는 가져온 소스 merge 여부
1. pull: 가져온 소스가 최신일 경우 현재 버전을 해당 소스에 맞춰 올림(merge)
2. fetch: 소스를 가져올 뿐 merge하지 않음
    git fetch <원격 저장소명>