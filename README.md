# for-utterances
블로그 댓글 관리를 위한 레포지토리

## 사연 - 새로운 댓글 플랫폼을 찾아보자..

나는 노션 블로그 호스팅 서비스 oopy를 사용하고 있다. https://www.oopy.io/ 
매우 만족중이고, 주위에도 권하고 있다.

하지만...... 노션 자체가 블로그 포스팅에 최적화된 플랫폼이 아니다보니, 불편한 점이 여럿 있는데 그중에 하나가 댓글이다.

oopy는 댓글 플러그인으로 disqus를 지원한다. 하지만 disqus를 겪어본 분들은 알겠지만 로그인이 힘들어 댓글 하나 달려면 피곤해진다. (실제로 [현구막](https://github.com/Hyeon9mak)이 댓글이 달기 힘들어서 댓글 달다 때려쳤다는 제보를!)

그리고.................. 무료로 사용하니 어느날부터 내 블로그에 광고를 달기 시작했다...... 매우 흉하다...

<img width="1430" alt="스크린샷 2021-12-05 오전 9 09 22" src="https://user-images.githubusercontent.com/51393021/144728627-e7536228-68a6-4ae6-8cf8-acbb5795eb0d.png">

훌륭한 서비스를 만들어주신 disqus 관계자 분들은 리스펙트 하지만 **비용 부담없이 모발이식 받아보실 분**을 보고있으면 괜히 심란해진다. 새로운 댓글 플랫폼을 찾아 나섰고, utterances라는 오픈소스를 발견하였다!

## 설명

> utterances github app을 사용하기 위해 만든 레포지토리!
 
utterances는 레포지토리의 이슈로 댓글을 관리할 수 있는 오픈소스이다 [깃헙 주소](https://github.com/utterance)

해당 리드미를 참고하면 된다 :p [소개 페이지](https://utteranc.es/)

---

하지만 재미로 같이 해볼까요? ㅎㅎ
등록 과정은 매우매우 간단하다.

1. github apps로 이동한다. https://github.com/apps/utterances

2. configure을 누른다.
  ![image](https://user-images.githubusercontent.com/51393021/144728698-f84d238e-c0e1-47d8-91ff-fe55d3493240.png)

3. 레포지토리 지정을 해주어야 하는데, 이 레포지토리 처럼 utterences용 레포지토리를 만들어주는 게 좋을 것 같다.
  ![image](https://user-images.githubusercontent.com/51393021/144728726-289cdfd4-c829-4e8f-8185-7d4ee601a1cc.png)

4. 등록을 마쳤다면, https://utteranc.es/ 로 이동해보자. 테마에 맞추어 스크립트를 생성할 수 있다. 맘에드는 이슈 생성 방법과 테마 등을 정하고, 스크립트를 복사하자.
  ![image](https://user-images.githubusercontent.com/51393021/144728768-d1647afe-2693-4063-8099-96836c0289f4.png)

5. oopy를 사용하는 경우, oopy 콘솔에서 html 삽입 body부분에 해당 스크립트를 넣어주면, 포스팅 가장 하단부에 댓글란이 생성된다! (github 블로그를 사용하시는 분은 원하는 위치에 해당 스크립트를 넣어주시라)
  ![image](https://user-images.githubusercontent.com/51393021/144728786-75677c2c-d04e-4e8f-97e8-3befae47e251.png)


## 실제 활용 사례

본문에 댓글을 달아보았다.. 마크다운도 지원해.. 대박적.. 감동받아버렸다

![image](https://user-images.githubusercontent.com/51393021/144728514-ea0cc755-8e6f-40e8-8bc3-ac6c7452ef15.png)

이슈로 등록되고.. 깃헙설정에 의해 메일로도 날아왔다.. 박박..짜짜..
![image](https://user-images.githubusercontent.com/51393021/144728527-83a1f5aa-aff8-4352-8531-40d993f9ac3a.png)

## 아쉬운 점
다만 디스쿠스를 이용할 땐 "홈화면에서만 노출되지 않도록" 하는 것이 간단했는데, 지금의 경우 메인페이지에도 댓글란이 노출된다. 해당 내용의 스크립트 처리를 해주어야 겠는데, 귀찮으니까 oopy에서 플러그인으로 만들어줘잉 ㅎ_ㅎ
