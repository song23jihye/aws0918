### AWS 머신 러닝

### 2번 소스 오류 수정
train_data = train_data.replace({True:1, False:0})
<br>
validation_data = validation_data.replace({True:1, False:0})
<br>
test_data = test_data.replace({True:1,False:0})
<br>
train_data
