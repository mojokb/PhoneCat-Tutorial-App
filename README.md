# PhoneCat-Tutorial-App
# Tutorial
 angularJs를 소개하기에 가장 좋은 방법은 angular web app을 만드는 튜토리얼을 따라해 보는 것입니다.
 앞으로 만들어 볼 앱은 안드로이드 기기들의 리스트를 뿌리고, 관심있는 기기들의 리스트만 보여주는 기능과 특정 기기의 상세를 보여주는 카탈로그입니다.
 <img src="https://docs.angularjs.org/img/tutorial/catalog_screen.png"></img>
 
 angular가 플러그인이나 네이티브 익스텐션의 사용없이 어떻게브라우저를 영리하게 만드는지 튜토리얼을 따라가봅시다.
 
 * 사용자의 액션에 즉시 바뀌는 동적뷰의 데이터를 만드는 client-size data binding 예제.
 * DOM 조작없이 데이터를 뷰에 어떻게 유지하는가
 * Karma 와 Protractor를 통해 웹앱을 테스트하기에 더 좋고 더 쉬운 방법을 배우기 
 * 의존성 주입 방법, 앱에 데이터를 넣는 것 같은 일반적인 web task을 더 쉽게 만드는 방법.
 
 이 튜토리얼을 마치게 되면 당신은,
 * 요즘의 브라우저에서 돌아가는 동적어플리케이션 작성이 가능하다.
 * 뷰에다 데이터 모델을 연결할수 있는 데이터 바인딩 사용이 가능하다.
 * Karma를 이용한 유닛테스트 생성, 실행이 가능하다.
 * Protractor를 이용한 end to end 테스트를 생성, 실행가능
 * 어플리케이션 로직을 템플린에서 컴포넌트와 컨트롤러로 이동할 수 있다.
 * Angular로 구성된 서버에서 데이터를 가져올 수 있다.
 * ngAnimate 모듈을 통해 애플리케이션에 애니메이션을 적용할 수 있다.
 * 좀 더 큰 프로젝트에 걸맞는 구조화된 angular 어플리케이션을 설계할 수 있다.
 * angularJS학습을 위한 자료들을 식별할수 있다.
 
 이 튜토리얼은 end 2 end 테스트와 작성 및 실행 유닛을 포함하는 간단한 어플리케이션을 만드는 전체 프로세스를 설명합니다.
 각 단원의 끝에 있는 실험들은 작업중인 어플리케이션과 angularJS에 대해 좀 더 배우기 위한 의견을 제공합니다.

 몇시간을 통해 전체 튜토리얼을 할 수 도 있으며, 줄겁게 하루동안 파고들지도 모릅니다. 만약 좀 더 짧은 설명을 원하신다면
 Getting started 문서를 참고하세요.
 
 ## 환경설정
 이제 로컬머신에 개발환경을 설정해 봅시다. 튜토리얼로 바로 가고 싶으시면, 처음 단계로 가실수 있습니다.
 https://docs.angularjs.org/tutorial/step_00 

 ## Working with the code
 이 튜토리얼을 따라갈 수도 있고 로컬에서 코드를 수정할 수 있습니다. 이번엔 실제로 테스팅 툴을 사용하여, angular code를 작성할 수 있습니다. 
 
 튜토리얼은 소스코드관리를 위해 GIT을 기반으로 합니다. 튜토리얼에서는 git에 대해서 설치, 실행, 몇몇의 git명령어만 알면 됩니다.
 
 ## GIT 설치하기
 http://git-scm.com/download 에서 Git을 설치/ 다운로드 가능합니다. 한번 설치되면  git 커맨드 라인툴에 접속해야합니다.
 사용에 필요한 주요 명령어는
 * git clone ... : 원격 저장소에서 로컬머신으로 복제합니다.
 * git checkout ... : 특정 브랜치나 태깅버젼의 코드를 체크아웃합니다.
 
 ## angular-phonecat 다운로드
 https://github.com/angular/angular-phonecat 에서 복제.
<pre><code>
git clone --depth=16 https://github.com/angular/angular-phonecat.git
</code></pre>
 

 
# 0 - Bootstrapping
# 1 - Static Template
# 2 - Angular Templates
# 3 - Components
# 4 - Directory and File Organization
# 5 - Filtering Repeaters
# 6 - Two-way Data Binding
# 7 - XHR & Dependency Injection
# 8 - Templating Links & Images
# 9 - Routing & Multiple Views
# 10 - More Templating
# 11 - Custom Filters
# 12 - Event Handlers
# 13 - REST and Custom Services
# 14 - Animations
# The End
 
