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