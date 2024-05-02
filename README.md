## 01.-metadata.html
link : http://127.0.0.1:5501/01-metadata.html
## 02-heading-paragraph.html
link : http://127.0.0.1:5501/02-heading-paragraph.html
## 03-image-figure.html
link : http://127.0.0.1:5501/03-image-figure.html
## 04-unordered-ordered-list.html
link : http://127.0.0.1:5501/04-unordered-ordered-list.html 
## 05-definition-list.html
link : http://127.0.0.1:5501/05-definition-list.html
## 06-anchor.html
link : http://127.0.0.1:5501/06-anchor.html
- _blank는 새 탭으로 링크를 열겠다는 의미임 하지만 언더바를 뺏음에도 불구하고 새 탭으로 열림, 심지어 오타를 내도 새 탭으로 링크가 열린다 why? target 안에 열고싶은 탭창의 이름이 중복되어있으면 새로 열지 않는다.
## 07-blockquote-br.html
link : http://127.0.0.1:5501/07-blockquote-br.html
- 화면상에서는 <미생> <>으로 감싼게 같지만, 문법상으로 오류가 있기 때문에 &을 사용해야한다.
## 08-phrasing-element.html
link : http://127.0.0.1:5501/08-phrasing-element.html
## 09-section-main.html
link : http://127.0.0.1:5501/09-section-main.html
## 10-container-element.html
link : http://127.0.0.1:5501/10-container-element.html
## 11-text-level-element.html
link : http://127.0.0.1:5501/11-text-level-element.html
## 12-address.html
link : http://127.0.0.1:5501/12-address.html
## 13-picture-source.html
link : http://127.0.0.1:5501/13-picture-source.html
## 14-video-source.html
link : http://127.0.0.1:5501/14-video-source.html
- track 태그 자막을 말한다 자막 파일의경로 vtt 확장자를 가지고 있음
kind, 여기 보여지는 트랙이 자막이다 라고 알려줌
- controls 비디오 기능 추가 , autoplay 하면 자동재생 muted 라는 속성을 준다 음소거 자동재생을 킬려면 반드시 음소거를 걸어줘야한다  접근성 때문에 크롬 브라우저 정책에서 바뀜 
- 사용자 경험 보호: 사용자가 의도치 않게 시끄러운 소리로 인해 불편을 겪을 수 있다 muted 속성은 이러한 상황을 방지
- 브라우저 정책 : 많은 웹 브라우저는 사용자 경험을 보호하기 위해 자동 재생 비디오에 대한 제한을 두고 있다
특히, 사용자가 이전에 사이트에서 상호 작용한 적이 없거나, 자동 재생이 활성화된 사이트를 처음 방문하는 경우, muted 속성이 없으면 자동 재생을 차단할 수있다 

## 15-iframe.html
link : http://127.0.0.1:5501/15-iframe.html
## 16-map-area.html
link : http://127.0.0.1:5501/16-map-area.html
## 17-table.html
link : http://127.0.0.1:5501/17-table.html
## 18-form.html
link : http://127.0.0.1:5501/18-form.html
- 웹 접근성 차원에서 바라보면 명시적으로 작성하는게 좋다   
오래된 통신 기기는 아직 암시적 방식을 지원하지 않는다   
- 명시적인 방식 for 속성을 사용하여 label과 input 연결   
input 요소와 label의 관계가 명확해짐, 스크린리더에서 잘 인식되므로 접근성 향상   
- 암시적 방식 input 요소를 label 요소 내에 포함되는 방식   
덜 명확하다, label 요소와 input 요소를 함께 그룹화해야 하므로, 디자인 및 레이아웃에 일부 제약이 있을 수 있다.
## 19-interactive-element.html
link : http://127.0.0.1:5501/19-interactive-element.html
## 20-scripting.html
link : http://127.0.0.1:5501/20-scripting.html
## 21-interactive-attribute.html
link : http://127.0.0.1:5501/21-interactive-attribute.html
- 유저 인터렉션 속성   
사용자와 상호작용 할 수 있도록 만들어주는 속성
hidden, tabindex, accesskey, contenteditable, draggable 속성들이 대표적인 속성이다
- tabindex   
-1 로 설정해주면 상호작용이 가능한 요소라도 포커스가 이동 X    
양수값을 설정하여 요소들 간에 포커스가 잡히는 순서를 강제 변환 가능
0 으로 설정하면 div,span 과 같이 tab 키로 포커스가 불가능한 요소를 기반으로 구현한 후 포커스 설정 가능
## 22-external-style.html
link : http://127.0.0.1:5501/22-external-style.html
## 23-embeded-style.html
link : http://127.0.0.1:5501/23-embeded-style.html
## 24-inline-style.html
link : http://127.0.0.1:5501/24-inline-style.html
## 25-selector.html
link : http://127.0.0.1:5501/25-selector.html
