# 3주차 git
         
## 이미지
![kau](./image/kau.jpg)
   
## 링크
[LMS](https://lms.kau.ac.kr/)
   
## ProGit 링크
[ProGit](https://git-scm.com/book/ko/v2)
   
## 주요 git 명령어
### git 기본 명령어   
sudo apt install git : git 설치   
git status : 현재 상태 확인   
git log : 전체 로그 확인   
git init : git 저장소 생성하기   
git clone 주소 : 저장소 복제 및 다운로드   
   
### git branch 관련 명령어   
git branch 브랜치명 : 브랜치 생성   
git checkout 브랜치명 : 해당 브랜치로 이동   
git branch -d 브랜치명 : 브랜치를 생성하고 해당 브랜치로 바로 이동   
git branch -a : 모든 브랜치 확인   
git add . : 파일 및 폴더 add   
git commit -m "commit message" : 커밋   
git branch -d 브랜치명 : 브랜치 삭제   
git merge 다른 브랜치명 : 현재 브랜치에 다른 브랜치 수정사항 병합   
   
### git config 설정 관련 명령어   
git config --global user.name "이름" : git config 설정하는 방법   
git config --global user.name "이메일주소" : git config 설정하는 방법   
git config --list : 전체 config 리스트 확인   
git config --unset user.name : git config 삭제하기   
git config --unset user.email : git config 삭제하기   
    
## W2 과제 코드
```
#! /usr/bin/env bash
  1 file_path=$(find ~ -name "w2_homework.txt" 2> /dev/null)
  2 line_number=$(wc -l < $file_path)
  3 last_line=$(tail -n 1 $file_path)
  4
  5 echo "----------"
  6 echo "name :"
  7 echo "문 채 영"
  8 echo " "
  9 echo "----------"
 10 echo "student id :"
 11 echo "2022125018"
 12 echo "----------"
 13 echo " "
 14 echo "file path :"
 15 echo "$file_path"
 16 echo " "
 17 echo "----------"
 18 echo "line number :"
 19 echo "$line_number"
 20 echo " "
 21 echo "----------"
 22 echo " "
 23 echo "last_line"
 24 echo "$last_line"   
```
   
## 마크다운
### 목록
#### 번호 있는 목록 : 내림차순 정렬
1. 첫번째
3. 세번째
2. 두번째

#### 번호 없는 목록 : *, -, +
* 첫번째
- 세번째
+ 두번째
-----
* 빨강
  * 녹색
    * 파랑

### 강조
*single asterisks*    
_single underscores_    
**double asterisks**    
__double underscores__    
~~cancelline~~   
