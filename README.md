score = input("점수를 입력하시오:")
num_score = int(score)

if num_score >= 71 :
    print("A")
elif num_score >= 41 and num_score <= 70:
    print("B")
elif num_score >= 11 and num_score <= 40:
    print("c")
else:
    print("D")