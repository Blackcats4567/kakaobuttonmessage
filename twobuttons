<html>
<head>
	<title>카카오톡 버튼있는 메시지 전송하기</title>
<script id="javascript-sdk" src="https://developers.kakao.com/sdk/js/kakao.min.js"></script>
</head>
<body>
	<p><strong>아래 카카오톡 아이콘을 눌러 전송하세요</strong> By. Blackcats4567</p>
<a id="kakao-link-btn" href="javascript:sendLink()">
  <img
    src="https://developers.kakao.com/assets/img/about/logos/kakaolink/kakaolink_btn_medium.png"
  />
</a>
<script type="text/javascript">
 Kakao.init('3b5dfa9a81e8e4995342673d34fa85be');
  function sendLink() {
    Kakao.Link.sendDefault({
      objectType: 'feed',
      content: {
        title: '이런 버튼있는 메시지',
        description: '이런 메시지를 보내고 싶다고요? 아래 버튼을 눌러 방법을 알아보세요',
        imageUrl:
          'https://blackcats4567.github.io/deadcat/2020-06-06_19.08.30.png',
        link: {
          mobileWebUrl: 'https://youtu.be/BpAe8d-CXKk',
          webUrl: 'https://youtu.be/BpAe8d-CXKk',
        },
      },
      social: {
        likeCount: 99999, //99999가 최대입니다
        commentCount: 99999, //99999가 최대입니다
        sharedCount: 99999, //99999가 최대입니다
      },
      buttons: [
        {
          title: '버튼1',
          link: {
            mobileWebUrl: 'https://youtu.be/BpAe8d-CXKk',
            webUrl: 'https://youtu.be/BpAe8d-CXKk',
          },
        },
        {
          title: '버튼2',
          link: {
            mobileWebUrl: 'https://youtu.be/BpAe8d-CXKk',
            webUrl: 'https://youtu.be/BpAe8d-CXKk',
          },
        },
      ],
    })
  }
</script>
<!-- www.blackcats4567.com -->
<!-- 이미지/버튼 클릭 시 주소는 Kakao Developers의 애플리케이션 > 플랫폼 > Web에 넣어야 클릭했을때 성공적으로 표시됩니다 -->
  </body>
</html>
