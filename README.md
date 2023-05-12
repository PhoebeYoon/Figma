# Figma
## 🍑 Color models in Figma

웹에서는 컬러를 표현하는 방식으로 RGB를 사용합니다.  
빛의 삼원색을 뜻하는 말이며 **빨간색(Red), 초록색(Green), 파란색(Blue)** 의 합성어입니다.    
색광에서 빨간색과 초록색을 합치면 노란색(Yellow)이 되고, 초록색과 파란색을 합치면 청록색(Cyan)이 되며, 파란색과 빨간색을 합치면 자홍색(Magenta)[1]가 된다. 그리고 세 가지 색을 모두 합치면 흰색(White)이 되고, 반대로 세 가지 색을 모두 제외하면 검은색(Black)이 됩니다.

이런 식으로 텔레비전이나 컴퓨터의 모니터 등 영상 장치의 해상도를 조절하는 표시 장치에 사용된다. 또한 빛을 이용하는 장치가 아닌 인쇄 매체의 경우에는 잉크체계를 사용해 특정 색을 흡수하고 나머지를 반사하기 때문에 RGB가 아닌 **CMYK**가 적용됩니다.

<img width="300" alt="스크린샷 2023-05-12 오후 9 24 11" src="https://github.com/PhoebeYoon/Figma/assets/48478079/8c97f431-20f2-4e81-bd6c-888410af0147">

<br /><br />
<img width="150" alt="스크린샷 2023-05-12 오후 9 33 20" src="https://github.com/PhoebeYoon/Figma/assets/48478079/2824df07-ce9d-474a-af85-a4f0b397a88f">


### RGB   
RGB or Red Green Blue 
### HSB   
Hue(색조) Saturation(채도) Brightness (밝기)

### HSL   
Hue(색조) Saturation(채도) Luminance  (빛의 밝기 )
### CSS에서 사용하는 방식으로 Red, Green, Blue, Alpha 를 뜻합니다
예) rgba(47, 128, 237, 1) 각 컬러의 값은 최소 0 부터 최대 255의 숫자를 갖습니다. 

그래서 알파를 제외하고 rgb (255,0,0)로 표현된다면 빨간색을 최대치로 삽입하고 나머지 녹색과 파란색은 0으로 전혀 색상을 섞지 않는다는 의미입니다.  
