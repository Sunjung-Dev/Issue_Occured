# Issue2 

dataframe -> json 형태로 변환하기 


    df = df.to_json() 

  
이렇게 변환할 경우 row 를 기준으로 저장되게 됨. 

내가 원하는 방식은 열을 기준으로 저장하고 싶음.

그럴때 쓰는 옵션이 따로 있음. 
'''
df = df.to_json(orient='records')
'''
