# 대학생을 위한 웹 개발 공부용 체크리스트

제가 2012년부터 대학교 3학년 대상으로 강의를 하고 있습니다. 들어보니 요즘 전산 관련학과 학생들은 1년 정도 휴학이 기본이라고 하더군요. 원래 개발을 잘하는 친구들이야 알아서 뭔가 하겠지만, 대부분의 경우 학과에서 배우는 것만으로는 뭔가 부족하다고 느껴서 휴학을 하고 뭔가를 해보려고 한답니다. 하지만 휴학에서 돌아온 친구들에게 물어보면, 딱히 뭔가를 했다는 것을 듣기가 어렵습니다. 누구의 도움 없이, 잔소리 없이 개발 공부를 한다는 것은 참 어렵습니다. 더구나 웹 개발은 너무나 방대해서,뭘 해야 할지도 잘 모를 겁니다.

그래서 아직 개발에 익숙하지 않은 전산과 대학생들에게, 뭘 해보면 좋을 지를 알려주는 체크리스트를 주면 어떨까 하는 생각이 들어서 이번에 휴학하는 친구들을 실험 대상으로 삼아서 만들어 보고 있습니다. 물론 본인의 노력이 있다면 휴학하지 않고도 가능할 것 같습니다 ;)

이 리스트는 개발의 원리를 깊숙이 이해하는 것을 목표로 하기 보다는, 웹 기술 자체에 대한 흥미를 느끼고 관련된 것들을 만들어 보면서 성장하는 것을 목표로 합니다.

혹시 이걸 따라해 볼 대학생 분들! 아래 항목들만 따라하기 보다는 각 항목에 나오는 기술/단어/제품들에 대해서 가능한 상세히 살펴보는것을 권장합니다. 구글에 해당 단어만 치면 온갖 좋은 설명자료들이 튀어나올겁니다. 삽을 깊숙이 파는걸 두려워 하지 마세요.

*   **웹의 기본**

    웹 개발을 한다면 기본적으로 웹이 구동되는 기반 기술을 알고 있어야 합니다. 웹의 역사와 HTTP/HTML 의 발전에 관해서는 알아둬야죠.
    *   웹환경의 이해 (한양대 동영상 강의)- [http://www.youtube.com/watch?v=qK6wcQ8JEKc&amp;list=PLSN_PltQeOyg7v7OFTnq_Jdk_r0YXozrw](http://www.youtube.com/watch?v=qK6wcQ8JEKc&amp;list=PLSN_PltQeOyg7v7OFTnq_Jdk_r0YXozrw)
    *   웹을 지탱하는 기술 - [http://xguru.net/1033](http://xguru.net/1033) 동명의 책으로도 나와있습니다.
*   **Codecademy 기본 수강하기**

    최근엔 온라인에서 개발을 배워볼수 있는 많은 사이트들이 생기고 있습니다. 그중에서도 Codecademy 의 강의들은 웹개발을 시작하는 사람들에게 아주 도움이 됩니다. 아래 기본 세션 5개와 자신이 마음에 드는 언어 세션중 하나 ( 가능하면 모두 ) 를 들어보세요.

    *   HTML &amp; CSS - [http://www.codecademy.com/en/tracks/web](http://www.codecademy.com/en/tracks/web)
    *   Javascript - [http://www.codecademy.com/en/tracks/javascript](http://www.codecademy.com/en/tracks/javascript)
    *   jQuery - [http://www.codecademy.com/en/tracks/jquery](http://www.codecademy.com/en/tracks/jquery)
    *   Make a Website - [http://www.codecademy.com/skills/make-a-website](http://www.codecademy.com/skills/make-a-website)
    *   Make a Interactive Web site - [http://www.codecademy.com/skills/make-an-interactive-website](http://www.codecademy.com/skills/make-an-interactive-website)
    *   웹개발 언어 세션 하나 선택 해서 수강 - Python / Ruby / PHP 중 하나
*   **아마존에 EC2 인스턴스 만들기 - 돈안드는 마이크로 인스턴스로**

    일단 웹 개발을 시작하기 전에 자신이 만들 웹사이트가 들어갈 서버를 만들어 보는 것도 필요합니다. 예전엔 이런거 할때 Vmware/VirtualBox 같은 가상머신 설치하고 해보라고 했지만, 요즘은 그냥 바로 클라우드로 테스트 하는게 더 좋습니다. 아마존 웹서비스에 대해서 알아둔다 생각하고 관련된 것들을 가능한 많이 읽어보기를 권합니다. [생활코딩의 AWS 가이드](http://opentutorials.org/course/608/3002) 나 [아마존 웹 서비스를 다루는 기술](http://www.yes24.com/24/goods/14673234) 같은 책을 참고하셔도 됩니다만, 가능하면 한글화 되어있는 [아마존의 EC2 가이드](http://aws.amazon.com/ko/documentation/ec2/) 와 같은 공식 매뉴얼을 참고하셔서 직접 공부하면서 보시기를 권합니다.
    *   Ubuntu 인스턴스 만들어보기
    *   Apache 설치해 보기
    *   PHP 설치해 보기
    *   MySQL 설치해 보기 - ( AWS 에서는 RDS를 쓰는게 보통이겠지만, 설치 경험이므로 그냥 한번 설치해봅니다. )*   위의 Apache/PHP/MySQL 을 RedHat 인스턴스로 만들어서도 한번 해보면 좋습니다.
*   **아마존 EC2에 Wordpress 설치해 보기**

    개발하기 전에 방금 만든 서버에 자신이 쓸 블로그를 하나 설치해봅니다. 가입형 블로그가 아닌 설치형 블로그를 한번 만져보는 것도 도움이 됩니다.

    *   한개의 인스턴스에 MySQL로 설치해보기
    *   위 인스턴스 설정과 다르게 RDS/S3 이용하는 형태로 설치해보기 - [AWS에 워드프레스 설치하기](http://blog.juyeong.net/2014/02/23/aws%EC%97%90-%EC%9B%8C%EB%93%9C%ED%94%84%EB%A0%88%EC%8A%A4-%EC%84%A4%EC%B9%98%ED%95%98%EA%B8%B0/) 참고
    *   워드 프레스 설치후 글 3개 이상 써보기 - 위의 과정과 **앞으로 이 체크리스트를 따라하면서 겪은 일들/배운 점등을 적어보면** 어떨까요?
    *   필수 플러그인 뭔지 하나하나 자세히 알아보고 설치 해보기 - Akismet , WordPress SEO by Yoast, WP Super Cache , Jetpack by Wordpress, Google XML Sitemaps, Twitter Tools , WPTouch , Google Analytics for Wordpress
    *   맘에 드는 테마 하나 입혀보기
*   **자신의 도메인 등록 하고 사용하기**

    이제 위에서 만든 블로그를 자신의 주소로 만들어봅니다. 도메인을 구입하고, 네임서버에 등록하고 하는 과정을 알아봅니다. 그리고 가능하면 자기 도메인으로 이메일주소를 만들어서 사용해 봅니다. 개발자라면 이력서에 naver.com/gmail.com 보다는 자신의 도메인 메일 주소가 있는게 더 좋지 않을까요 ? ^^

    *   자신의 도메인 구입해서 등록해보기 ( SiteX.com 과 같은 형태의 도메인 )
    *   DNSEVER 에 가입하고 자신의 DNS 서버로 등록해보기
    *   자신의 EC2 인스턴스에 Public IP 등록하고 위의 도메인을 연결해보기 ( blog.SiteX.com )
    *   자신의 도메인에 구글앱스 등록해보기. 지메일,캘린더 등을 자신의 도메인에 사용(30일간만 무료, 계속 사용시 월 $5 필요)
    *   구글앱스 대신 네이버 Works 무료 사용가능 [https://works.naver.com/](https://works.naver.com/)
*   **직접 웹 사이트 만들어 보기 ( 뒤에는 SiteX 라고 부르겠음 )**

    웹사이트 만들기는 정작 내용이 많지 않습니다. 하지만 이 튜토리얼중 아마도 가장 오래걸릴지도 모릅니다. 앞에 Codecademy 에서 배운 인터랙티브 웹사이트 같은것을 한번 만들어 보는걸 목표로 합니다. 자신이 간단한 아이디어를 내고 그걸 구현해 보는 것도 좋고, 다른 유명한 서비스를 한번 따라해서 만들어 보는것도 좋습니다. 아이디어를 내고 개발에 들어갔다면 개발하면서 다음 단계를 같이 병행하세요.

    *   손에 익은 개발 언어로 EC2인스턴스에 간단한 웹사이트 구현 - 복잡한것 말고 간단한 것으로 ( 체크리스트 , 간단한 게시판등 )
    *   [http://getbootstrap.com/](http://getbootstrap.com/) 활용해서 디자인 신경쓰지 말고 만든다.
    *   프론트엔드
        * [Angular.js](http://angularjs.org/)(_추천_)
        * [Backgone.js](http://backbonejs.org/)
        * [Ember.js](http://emberjs.com/)
    *   백엔드(_웹개발 구조의 기본인 MVC(Model-View-Controller) 개념을 처음 익히는데 Rails의 Getting Started를 한번 따라해보는 것을 권합니다_)
        * [Python+Django](https://www.djangoproject.com/)
        * [Python+Flask](http://flask.pocoo.org/)
        * [Node.js + Express](http://expressjs.com/)
        * [Ruby + Rails](http://guides.rubyonrails.org/getting_started.html)
    *   DNSEVER 에서 이 웹사이트를 www.SiteX.com 으로 연결해보기
    *   DB가 필요한 사이트가 대부분이므로 MySQL 사용법 공부 - [생활코딩의 MySQL강의](http://opentutorials.org/course/195/1467)
*   **Git 공부하기**

    아마 앞에서 웹사이트를 그냥 만들어 봤다면, 소스를 저장하고 버전별로 관리하는게 어렵다는걸 느꼈을겁니다. 이제 Git 을 배워봅니다.

    *   버전관리를 들어본적 없는 사람들을 위한 DVCS [http://www.slideshare.net/ibare/dvcs-git](http://www.slideshare.net/ibare/dvcs-git)
    *   Git 간편안내서 [http://rogerdudler.github.io/git-guide/index.ko.html](http://rogerdudler.github.io/git-guide/index.ko.html)
    *   Pro Git 한글판 [http://dogfeet.github.io/articles/2012/progit.html](http://dogfeet.github.io/articles/2012/progit.html)
    *   완전초보를 위한 GitHub [https://nolboo.github.io/blog/2013/10/06/github-for-beginner/](https://nolboo.github.io/blog/2013/10/06/github-for-beginner/)
    *   SiteX 의 코드를 GitHub 에 올려보기
    *   GitHub의 팁들 살펴보기 [https://github.com/tiimgreen/github-cheat-sheet/blob/master/README.ko.md](https://github.com/tiimgreen/github-cheat-sheet/blob/master/README.ko.md)
    
*   **Facebook 관련 개발 알아보기**

    페이스북은 10억 이상이 쓰는 거대한 SNS 이기도 하지만, 웹 환경에서 다양한 기능을 통해 수많은 웹사이트들과 연결되어 있습니다. 일반 웹사이트에 붙어있는 좋아요 버튼이 어떻게 동작하는지 알아보고,좋아요 버튼을 내 웹사이트에 붙여봅니다. 아예 로그인을 페이스북으로 하는 웹사이트를 만들어 봐도 좋습니다. 페이스북은 이제 자신이 만드는 웹사이트와 떼어낼 수 없는 관계입니다.

    *   웹에 페이스북 좋아요 버튼 달기 - [https://developers.facebook.com/docs/plugins/like-button?locale=ko_KR](https://developers.facebook.com/docs/plugins/like-button?locale=ko_KR)
    *   페이스북 소셜 플러그인 나머지 (공유하기,댓글 등 ) - [https://developers.facebook.com/docs/plugins?locale=ko_KR](https://developers.facebook.com/docs/plugins?locale=ko_KR)
    *   페이스북 로그인 - [https://developers.facebook.com/docs/facebook-login/v2.2?locale=ko_KR](https://developers.facebook.com/docs/facebook-login/v2.2?locale=ko_KR)
    *   SiteX 에 좋아요 버튼 달기
    *   SiteX 에 페이스북 댓글 달기
    *   SiteX 에 페이스북 로그인 달기
    *   SiteX 의 공식 페이스북 페이지 만들기 - [https://business.facebook.com](https://business.facebook.com) 자신을 관리자로 등록
    *   SiteX 의 각 페이지에 OpenGraph 메타태그 적용하기 - [https://developers.facebook.com/docs/sharing/best-practices?locale=ko_KR](https://developers.facebook.com/docs/sharing/best-practices?locale=ko_KR)
*   **Twitter 관련 개발 알아보기**

    트위터 역시 다양한 웹사이트들과 연결이 됩니다. 공유버튼,트위터 카드등을 한번 적용해 보고, 자신이 만든 사이트에 새로운 글이 올라오면 자동으로 트윗하는 API 연동기능을 개발해 봅니다.

    *   트위터 공유 버튼 만들기 [https://dev.twitter.com/web/tweet-button](https://dev.twitter.com/web/tweet-button)
    *   SiteX 에 Twitter Card 적용해보기 [https://dev.twitter.com/cards/overview](https://dev.twitter.com/cards/overview)
    *   SiteX 에 새로운 콘텐츠 등록시 Tweet 되도록 API 사용해서 만들어보기 [https://dev.twitter.com/rest/reference/post/statuses/update](https://dev.twitter.com/rest/reference/post/statuses/update)
*   **Google Analytics 공부하기**

    내가 만든 웹사이트에 어떤 사람들이 오는지 통계를 확인하는데에는 Google Analytics 가 가장 유명합니다. 이건 구글이 직접 만든 강좌를 통해서 GA 에 대해서 알아보고, 자신이 만든 사이트에 GA를 설치해봅니다. 그리고 Funnel 이라는 것을 이해하고, 자신의 사이트에 방문한 사용자들이 주 목적 페이지 (쇼핑몰이면 결제완료페이지, 일반 사이트라면 회원가입완료 페이지 등)에 얼마나 도달하는지 알아봅니다.

    *   Digital Analytics Fundamentals - [https://analyticsacademy.withgoogle.com/course01](https://analyticsacademy.withgoogle.com/course01)
    *   Google Analytics Platform Principles - [https://analyticsacademy.withgoogle.com/course02](https://analyticsacademy.withgoogle.com/course02)
    *   [https://support.google.com/analytics/?hl=ko#topic=3544906](https://support.google.com/analytics/?hl=ko#topic=3544906)
    *   SiteX 에 GA 설치
    *   SiteX 에서 회원가입 완료 화면에 얼마나 도달하는지 Funnel 만들어서 보기
*   **SEO - Search Engine Optimization 알아보기**

    사람들이 내 사이트에 어떻게 처음으로 방문할까요? 광고나 누군가의 소개를 통하지 않는다면, 대부분 인터넷 검색을 통해서 찾아오게 됩니다. 구글 검색엔진에서 내 사이트가 잘 보이게 하려면 어떻게 하는지를 배워봅니다.

    *   구글이 직접 공개하는 [SEO 스타터 가이드 한글판](http://static.googleusercontent.com/media/www.google.com/ko//intl/ko/webmasters/docs/search-engine-optimization-starter-guide-ko.pdf)
    *   구글의 [SEO 도움말 페이지](https://support.google.com/webmasters/answer/35291?hl=ko)
    *   [스타트업을 위한 SEO 10분 가이드](http://googledevelopers.blogspot.ca/2012/06/seo-essentials-for-startups-in-under-10.html)
    *   제가 예전에 발표한 [모바일 시대의 SEO 전략](http://www.slideshare.net/xguru/mobile-seo-search-engine-optimization-16106439)
*   **온라인 마케팅 공부하기 with 구글 Adwords**

    내가 만든 사이트에 아무도 오지 않는다면, 웹에서 광고를 한번 해봅니다. 구글의 돈줄인 Adwords 에 대해 알아보고, 내가 만든 사이트를 한번 적은 금액으로 광고해봅시다. Conversion Tracking 이라는 것을 이해하고, 광고를 통해 얼마나 많은 사람들이 내 사이트의 회원이 되는지, 상품을 구매하는지 등을 알아보는 것이  가능하다는걸 배워봅니다.

    *   [https://support.google.com/adwords/answer/3436345?hl=ko](https://support.google.com/adwords/answer/3436345?hl=ko)
    *   [https://support.google.com/adwords/answer/4487079?hl=ko](https://support.google.com/adwords/answer/4487079?hl=ko)
    *   [https://support.google.com/adwords/answer/6028379?hl=ko](https://support.google.com/adwords/answer/6028379?hl=ko)
    *   SiteX 를 구글 광고 하나 만들어서 하루에 500원만 광고 돌려보기 ( 키워드 광고 와 디스플레이 광고 )
    *   Conversion Tracking 해보기 [https://support.google.com/adwords/answer/1722054?hl=en](https://support.google.com/adwords/answer/1722054?hl=en)

아직 실험대상?들이 이걸 시행해본게 아니어서 계속 추가되고 변경될 것 같습니다. 

도움 주실 개발자 분들은 풀리퀘 날려주세요 ;)

[원 소개글 http://xguru.net/1897](http://xguru.net/1897)
