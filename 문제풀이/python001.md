
# 정수 5개 입력해서 합 구하기
total = 0

for i in range(5):
    num = int(input("정수를 입력하세요: "))
    total += num

print("입력한 정수의 합은", total, "입니다.")
정수를 입력하세요: 1
정수를 입력하세요: 10
정수를 입력하세요: 15
정수를 입력하세요: 20
정수를 입력하세요: 30
입력한 정수의 합은 76 입니다.

#짝수 합 구하기
l=[]
for i in range(0,100,2):
    l.append(i)

my_list=l
my_list_sum=sum(my_list)
my_list_sum

2450

#*으로 트리 만들기
for i in range(6):
    print('*'*i)
*
**
***
****
*****

#숫자 배열 만들기
for i in range(1, 6):
    for j in range(i):
        print(i, end=' ')
    print()
1 
2 2 
3 3 3 
4 4 4 4 
5 5 5 5 5 

#구구단 7단 뽑기
for i in range(7,8):
    for j in range(1,10):
        print(i,'x',j,'=', i*j)

#리스트에서 숫자 뽑아서 카운트
ㅣ=[1, 3, 2, 1, 5, 1]
get=1
count=0

for num in l:
    if num == get:
        count+=1
print(count)

#입력받은 숫자 역순
num = int(input("정수를 입력하세요: "))

reversed_num = int(str(num)[::-1])

print("입력한 숫자의 역순은", reversed_num, "입니다.")

#입력한 숫자 합
x=int(input('숫자를 입력하세요'))
y=int(input('숫자를 입력하세요'))
def f(x, y):
    z=x+y
    return z

f(x, y)

#반지름 입력받아서 둘레 구하기
반지름=int(input('반지름을 입력하세요'))
π=3.14159
def f(반지름):
    반지름합=π*반지름**2
    return 반지름합

f(반지름)

#짝수, 홀수 나타내기
num=int(input('숫자를 입력하세요'))
def f(num):
    if num%2 ==0:
        print('짝수 입니다')
    else: print('홀수 입니다')
f(num)

#리스트 합 구하기
l=[1, 2, 3, 4]

def total_sum(l):
    total=0
    for i in l:
        total+=i
    return total

result=total_sum(l)
print(result)
