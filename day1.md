# git & github 특강 1일차 정리 
1. git init #관리시작(디렉토리당 1번만)
2. git status # 파일상태 확인
3. git add (git add .) # 무대위로 올리기
4. git commit -m "커밋사유" # 변경사항기록 (vim빠져나오기 esc+q)
5. config 설정(1번)
   - git config --global user.email "@"
   - git config --global user.name " "
   - git config --global --list
6. git log # 커밋의 내역확인
7. git log --oneline
8. git diff #커밋비교
9. github와 연결
    - git remote add origin URL
    - git remote -v
    - git push origin master
- #remote삭제
    - git remote rm origin
  