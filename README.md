# 2024.03.28

# 7과목의 점수를 입력 받습니다.
scores = []
for i in range(1, 8):
    score = int(input(f"{i}번째 과목의 점수를 입력하세요: "))
    scores.append(score)

# 합계 계산
total_score = sum(scores)

# 평균 계산
average_score = total_score / len(scores)

# 결과 출력
print("입력한 점수:", scores)
print("합계 점수:", total_score)
print("평균 점수:", average_score)

1번째 과목의 점수를 입력하세요: 80
2번째 과목의 점수를 입력하세요: 90
3번째 과목의 점수를 입력하세요: 70
4번째 과목의 점수를 입력하세요: 95
5번째 과목의 점수를 입력하세요: 88
6번째 과목의 점수를 입력하세요: 98
7번째 과목의 점수를 입력하세요: 92
입력한 점수: [80, 90, 70, 95, 88, 98, 92]
합계 점수: 613
평균 점수: 87.57142857142857
