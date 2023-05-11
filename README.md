# Figma
## 🍑 수업순서
- Figma 도구 리뷰
- 펜툴 연습 
- 파일 브라우저(File Browser)
- 외부 디자인 파일 불러오기(Sketch, Adobe XD 등)
- 도구 인터페이스(Tool Interface)
- 캔버스(Canvas)
- 프레임(Frame)
- 레이아웃 그리드(Layout Grid)
- 뷰 옵션(View Options)
- 이동 / 크기 변경(Moving & Scaling)
- 중첩(Nested) 프레임 / 슬라이싱(Slicing)
- 도형(Shapes) 그리기
- 펜(Pen), 연필(Pencil)로 그리기
- 텍스트(Text)
- 이미지(Images) 가져오기
- 이미지 마스킹(Masking)
- 레이어(Layers) 관리
- 컬러(Colors)
- 이펙트(Effects)
- 블렌딩(Blending)
- 스타일(Styles)
- 컴포넌트(Component)
- 자동 배치(Auto Layout)
- 플러그인(Plugins)

### 🎃 먼저 알자. 컴퓨터에서 사용되는 용어들

교재에서  http://uidesignguides.com/ppi-dpi-dp-sp-pt란-무엇일까 
우리가 만드는 ui디자인이 적용되는 대상은 웹페이지, 모바일에 있는 앱이지만 모니터의 해상도가 다양하고, 모바일도 사이즈가 매우 다양합니다.

화질은 결정하는 것은 한가지만은 아니지만 '화소밀도'가 높을수록 화면은 선명해집니다. 스크린의 사이즈와 해상도, 화소 밀도는 비례하지 않고 기기마다 다릅니다.

**이것은 기억하세요**

- PPI(Pixels Per Inch) : 화소 밀도. 픽셀 밀도라고 번역하기도 합니다. 1 inch² 큐빅에 들어가는 **픽셀의 수**를 말합니다.
- 스크린 사이즈 : **스크린의 대각선 길이**를 인치로 표현합니다. ex) iMac 27 = 27’’
- 해상도(Resolution) : 스크린의 총 **픽셀수를** 말합니다. ex) iMac 27 = 2560 × 1440
- DP (Device Pixel) : 안드로이드 사이즈 단위. **PPI가 다른 디바이스에서 px로 표기하면 밀도가 클수록 작게 보입니다.** dp로 표기하면 동일한 비율로 표현합니다.

- px : 컴퓨터모니터에서 흔히 사용되는 단위로, 바탕화면 설정에 보면 가로 X 세로 = 모니터의 총 픽셀수
- em : 웹페이지 만들때 사용되는 단위로 px가 절대적 단위이고 em은 상대적인 단위로 부모엘리먼트의 기준에 의해 정해지는 단위입니다. 16픽셀은 1em 입니다
- rem : root em 으로 em이 부모 엘리먼트를 기준으로 하는 것에 비해 rem은 웹페이지의 root 인 html태그에서 결정됩니다. 
- https://cubic-bezier.com/ 애니메이션을 역동적으로 움직이기 위해 사용되는 함수를 생성해주는 사이트입니다.

- 애플과 구글에서는 앱을 만들때 자기들의 기준에 맞추어서 개발하도록 가이드라인을 제시하고 있습니다.  
http://uidesignguides.com/design-system-motion-principle/ 클릭 후 반드시 정독하시기 바랍니다.
(👁️ 과제입니다 )
