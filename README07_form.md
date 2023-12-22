
# input에 값이 바뀌어도 App.js는 다시 실행되지 않는다 -> 이런것을 react로 부터 제어받지 않는다고 해서 uncontroled component라고 한다

# input안의 내용이 useState의 상태값과 매칭되도록 맞춰주어야 한다

# input태그 에서는 onChange={(e)=>{setName(e.target.value)}}
# e -> 이벤트 받음, 상태의 값을 변경하기 위해 setName 함수를 사용하며 
# 사용자가 입력한 값을 상태값으로 적용하기 위해 e.target.value를 사용한다

![image](https://github.com/sonahyeonn/myreact/assets/147791395/3cd87778-154d-4148-ae3e-63114bec1614)



