# 2023_OSS
[3주차 강의](./w3)

## 이미지
![kau_image](C:\Users\문채영\Desktop\kau image.png)

## 링크
[LMS](https://lms.kau.ac.kr/)
## ProGit 링크
[ProGit](https://git-scm.com/book/ko/v2)
## W2 과제 코드
'''
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

'''
