# 데이터사이언스를위한AI | HANYANG_UNI

q1. Q4에서 reshape 부분은, x/y를 가공한 뒤에 1차원 벡터를 2차원으로 바꿔주면 되는걸까요?
a1. 네 맞습니다 reshape을 이용해 2차원으로 바꿔주시면 됩니다

q2. Q3에서 아까 x를 따로 선언 해야한다고 하신건가요?, X는 어떤 값인 건가요?
a2. 네 len(x) 나오기 이전에 x를 선언해야 합니다. x는 앞서 선언한 dataframe dfLoad의 X값들입니다, dfLoad에 "X"에 해당하는 값들이 있습니다. (dfLoad["X"])

c1. ipl1, ipl2는 ipl_data에서 numeric value들로 이루어진 리스트 두 개를 아무거나 잡으시면 됩니다. 예를 들어 ipl1은 ipl_data의 Rank 값들의 리스트를 np.array로 변환한 것, ipl2는 Year 값들의 리스트를 np.array로 변환한 것으로 정하시면 됩니다.
