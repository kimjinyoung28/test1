vscode 와 깃헙 원격 저장소 연동

git init ##초기화 (1회성)
git add . ##지금까지 텍스트에디터에서 작업한 모든 변경사항 추가
git commit -m "first commit" ##변경사항에 대한 설명
git branch -M main ##Repository 처음 만들때만 사용. 브랜치를 main 으로 중점을 두는 작업. (1회성)
git remote add origin https://github.com/kimjinyoung28/test2.git ##Repository 처음 만들때만 사용. 깃헙이랑 원격으로연동한다는 뜻.
git push -u origin main ss#깃헙 원격 저장소에 변경사항 최종 업로드.

브랜치 생성
git checkout -b “브랜치명” ##브랜치 생성
git checkout 브랜치명 ##해당 브랜치로 이동
git add . ##위와 동일
git commit -m "first commit" ##위와 동일
git push origin 브랜치명 ##깃헙 해당 브랜치로 최종 업로드