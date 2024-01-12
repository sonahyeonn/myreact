

![image](https://github.com/sonahyeonn/react/assets/147791395/78f03c31-a641-437e-8d16-26bf4f21e379)

# Navigate 사용방법 - 어떤 페이지로 강제 이동(리다이렉트)
: react-router-dom 의 component

![image](https://github.com/sonahyeonn/react/assets/147791395/944a0196-3388-4a2e-ba85-d37474a42285)


# useParams
# react-router-dom 의 hook

```
http://localhost:3000/products/1
```

# url주소에서 파라미터는 제일 뒤에 있는 1이라는 숫자이다. id값이 들어와 있다.
# 파라미터 값을 읽어와야 할 때 useParams - hook이다

![image](https://github.com/sonahyeonn/react/assets/147791395/dc8497b2-42c4-4634-a89e-bf66b3a6a1ad)

# 문법 -> ?
```
<img src={product?.img} alt="" />
```
product?.img -> product가 있으면 product.img를 출력하라
