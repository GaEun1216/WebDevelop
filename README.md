git 에 새로운 내용 올리기
git add . // 변경된 모든 파일 
git commit -m "message"
git push -u origin main // main에 push 하기
-u 플래그는 "업스트림(upstream)"을 설정하는 역할을 합니다.
이 플래그를 사용하면 로컬 브랜치와 해당하는 원격 브랜치를 연결하여,
이후에 git push 명령을 사용할 때 원격 브랜치를 명시하지 않아도 
기본적으로 설정된 업스트림 브랜치로 푸시함. 즉, -u는 한번만 써도 된다는 뜻
