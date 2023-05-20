https://school.programmers.co.kr/learn/courses/30/lessons/120826
https://school.programmers.co.kr/learn/courses/30/lessons/120849
https://school.programmers.co.kr/learn/courses/30/lessons/120826
https://school.programmers.co.kr/learn/courses/30/lessons/120807
#3항 연산자
def solution(num1, num2):
    return 1 if num1 == num2 else -1
https://school.programmers.co.kr/learn/courses/30/lessons/120583
def solution(array, n):
    
    return array.count(n)

https://school.programmers.co.kr/learn/courses/30/lessons/120585
def solution(array, height):
    data=len(list(filter(lambda x:x>height, array)))
    return data

https://school.programmers.co.kr/learn/courses/30/lessons/120906
def solution(n):
    count=0
    for i in str(n):
        count+=int(i)
        
    return count

https://school.programmers.co.kr/learn/courses/30/lessons/120864
import re

def solution(my_string):
    return sum(map(int, re.findall(r'[0-9]+', my_string)))

https://school.programmers.co.kr/learn/courses/30/lessons/120889
#삼각형의 완성조건
def solution(sides):
    sides.sort()
    if sides[0] + sides[1] <= sides[2]:
        return 2
    if sides[0] + sides[1] >= sides[2]:
        return 1

solution([199, 72, 222])

https://school.programmers.co.kr/learn/courses/30/lessons/120956
#옹알이(정규표현식)
import re

def solution(babbling):
    count = 0
    p = ["aya", "ye", "woo", "ma"]
    for i in babbling:
        print('------------')
        print(i)
        for pattern in p:
            i = re.sub(pattern, ' ', i)
            print(i)
        if i.replace(' ', '') == '':
            count += 1
    return count

https://school.programmers.co.kr/learn/courses/30/lessons/120913
#잘라서 배열로 저장하기
def solution(my_str, n):
    l=[]
    for i in range(0,len(my_str),n):
        l.append(my_str[i:i+n])
    return l