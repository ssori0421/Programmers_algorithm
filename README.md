algorithm-study

repository 구조

프로그래머스

# 프로그래머스 문제풀이 작성 형식
./programmers/form.md
# 프로그래머스 문제풀이 작성
./programmers/level${num}/${problem_name}.md

codewars

# codewars kata form
./codewars/form.md
# codewars kata
./codewars/${num}kyu/${kata_name}.md
kata is problem


백준 알고리즘

# 백준 알고리즘 문제풀이 작성 형식
./baekjoon/form.md
# 각 문제들의 색인
./baekjoon/index.md
# 준 알고리즘 문제풀이 작성
./baekjoon/problem/{problem_num}_{problem_name}.md
백준 알고리즘의 문제들은 구분이 없기 때문에 문제에서 사용하는 알고리즘의 분류에 따라 index.md 파일에 작성합니다.


파일과 커밋 형식

모든 문제 풀이는 각 문제풀이 사이트마다 미리 작성해둔 form.md 파일을 참고하여 작성합니다.

해외 사이트 영어 문제들은 모두 영어공부를 위해 영어로 작성했습니다. 작성자의 영어실력에 한계가 느껴질 수 있습니다.

문제풀이한 파일과 index 파일을 업데이트하여 함께 커밋합니다. 커밋 메시지는 다음과 같습니다.

git commit -m "[site] problems"

site는 문제 풀이 사이트 problems는 구분이 가능하도록 문제의 이름을 작성합니다.

ex)

[baekjoon] 1248, 2529
[programmers] level2/가장큰수

알고리즘 트레이닝 사이트

국내

프로그래머스
https://programmers.co.kr/

Baekjoon Online Judge(백준알고리즘)
https://www.acmicpc.net/


해외

코드워즈
https://www.codewars.com/

릿코드
https://leetcode.com/
