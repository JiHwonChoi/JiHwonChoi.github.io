Web publishing project
======
HTML과 CSS를 통한 홈페이지 제작


### 개요
제작한 과제는 가상의 건축사무소 JIHWON CHOI ONECLICK ARCHITECTURE 의 홈페이지이다.

    
### home.html
홈페이지에서는 가장 강하게 어필하고 싶은 프로젝트를 배경이미지로 사용하였다. 

건축사무소의 이름을 헤더로 두었으며 footer 또한 페이지 하단에 구현하였다. 기본적인 홈페이지의 레이아웃과 footer에 대해서는 style-home.css 파일을 마련하여 정보를 저장하였다. 

좌측엔 네비게이션 바가 있다. 이미지를 누르면 홈으로 되돌아가고 나머지는 선택한 창으로 이동한다. 이곳엔 flex layout을 사용하여 항목들을 정렬하였다. Flex 의 align-items: stretch 를 이용해서 클릭 부분을 글자위치가 아니라 글자의 앞부분과 뒷부분 모두 길게 포함하여 클릭이 용이하게 디자인했다. 

네비게이션의 각 항목은 li 태그를 사용하여 구현 하였는데 css에서 아래쪽에 border line 을 주어서 선택이 용이하도록 했다. Border line은 마우스가 어디로 가면 되는지 알수 있도록 네비게이션 바 전체를 감싸도록 해 어디를 클릭해도 되는 것을 사용자에게 알려주려 했다. 

네비게이션의 클릭을 유도할 수 있도록 네비게이션엔 transition과 transform 기능을 적용하였다. 마우스를 가져다 대면 클릭할수 있는 부분의 글씨가 커지면서 배경색이 바뀐다. 이를 통해 자연스럽게 그 부분을 클릭해 다른 페이지로 넘어가도록 하였다. 이러한 정보들은 네비게이션 바를 따로 수정할수 있도록 nav.css 파일에 저장해두었다.
   
### about.html
이 페이지에서는 건축사무소의 디자인 철학에 대해 소개한다. 

건축물을 디자인 함에 있어 다양한 요소가 조화롭게 디자인 되었음을 표현하기 위해서 대표적인 3가지 항목을 따로 보여주고자 했다. 요소는 건물의 평면, 외벽 그리고 입면이다. 이것이 각각 중요하면서도 또 함께 하나의 건물, 프로젝트를 구성한다는 것을 알려주기 위해 배경에 이런 이미지를 사용하였고 z-index와 keyframe animation 효과를 사용하여 이러한 이미지들이 움직이도록 했다. 각각 움직이는 속도를 다르게 설정하여 이것이 하나가 되기도 했다가 따로 떨어지기도 하며 하나로써의 건물, 각각의 부분들을 강조하고자 했다. 이러한 움직임은 about-animation.css 파일에 저장해두었다.
 
### bim.html
이 페이지에서는 기본적인 용어들에 대해 이야기했다. 

이트에 접근한 사람들이 기본적인 정보를 얻을 수 있도록 간단하게 정보를 요약해 두었으며 이 페이지의 추후 수정등을 용이하도록 하기 위해 bim.css 파일을 따로 만들었다.
  
### Project.html
건축 사무실에서 진행한 작업들을 소개하는 페이지이다.

grid layout 을 사용하여 프로젝트를 보기 좋게 정리하였으며 프로젝트의 이름과 대표이미지 만으로 간단하게 정리하여 한눈에 파악하기 좋게 하였다. 이 페이지도 추후에 프로젝트마다 개별적으로 페이지를 만드는 등 업데이트를 하기 용이하도록 project.css 파일을 따로 두었다.
 
### Subscribe.html
사람들이 사무소에서 새로 작업한 프로젝트 뿐만 아니라 디지털 건축업계에서의 뉴스 또한 받을 수 있도록 subscribe 페이지를 만들었다. 사람들은 어떤 소식을 받을지 고를 수 있으며, 본인의 관심분야를 설정해 운영하는 측에서 이용자 파악을 할 수 있도록 했다.

### Responsive web design
이 홈페이지에서는 모바일에서도 편리한 이용환경을 위해 화면 폭이 600px 이하인 경우에 레이아웃이 변경된다.

화면 옆을 차지하고있던 네비게이션 바가 화면의 중앙으로 이동하고 컨텐츠가 그 아래로 이동하여 스크롤해서 페이지를 보기 편하게 디자인했으며 뒤의 이미지가 너무 가려지지 않게 네비게이션 바의 배경색을 없앴다.

모바일 버전에서는 헤더 부분의 긴 이름이 간단한 이름으로 바뀌어 화면에 맞게 조정된다. 이러한 정보는 header.css에 저장해 두었으며 추후에 헤더부분에 sns 등의 추가와 같은 업데이트가 용이하도록 했다. 

