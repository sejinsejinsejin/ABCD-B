# ABCD-B

파이썬을 사용하여 주어진 리스트에서 짝수를 필터링하고 결과를 출력하는 코드는 다음과 같습니다

numbers = [111, 26, 37, 48]

result = list(filter(lambda x: x % 2 == 0, numbers))

print(result)

이 코드를 실행하면 리스트 numbers에서 짝수만 필터링하여 result에 저장하고, result를 출력합니다. 결과는 [26, 48]가 됩니다.
