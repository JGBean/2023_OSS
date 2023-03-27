# 3주차 Git

## 이미지
![한국항공대학교](https://user-images.githubusercontent.com/122397387/227850460-70594bd7-fe3b-4320-b0c5-854f2405a90c.png)

## 링크
[LMS](https://lms.kau.ac.kr/)

## ProGit 링크
[ProGit](https://git-scm.com/book/en/v2)

## 주요 git 명령어
- add : 파일을 추적 대상으로 포함시킬 때, 또는 커밋 대상으로 포함시킬 때 사용
    - 예) git add
- commit
- branch
- merge
- status
- log
    - 예) git log --oneline --decorate --graph --all

## 2주차 과제
```bash
#!/usr/bin/env bash
echo "----------"
echo "name :"

echo

echo "----------"
echo "student id :"
echo 

file_path=`find /home/kau2/ -name w2_homework.txt 2> /dev/null`
echo "----------"
echo
echo "file path :"
echo $file_path
echo

line_num=`wc -l $file_path | cut -c 1 -`
echo "----------"
echo "line number :"
echo $line_num
echo

echo "----------"
echo "lask line :"
tail -n 1 $file_path
```
## 마크다운
### 목록
#### 번호 있는 목록:내림차순 정렬
1. 첫번째
2. 세번째
3. 두번째

#### 번호 없는 목록:*,-,+
- 첫번째
- 세번째
- 두번째

***
- 빨강
  - 녹색
    - 파랑

### 강조

*single asterisks* 

_single underscores_ 

**double asterisks** 

__double underscores__ 

~~cancelline~~


    
