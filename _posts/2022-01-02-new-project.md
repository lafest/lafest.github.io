---
title: "새로운 프로젝트 첫 삽"
date: 2022-01-02 23:30:00 +0900
categories: 3matchset frontend
---

지인분이 만든 페이지를 보고 욕심이 생겼다.

나는 (부끄럽게도) 여지껏 개발하며 나만의 서비스를 외부에서 접속할 수 있는 형태로 배포해본적이 없다.

그렇기 때문에, 뭐가 됐던 일단 '배포'하는 것을 배우고싶어서 무작정 레포를 하나 팠다.

https://github.com/lafest/3-match-set

간단한 보드게임 포팅 정도를 생각하고 레포를 판 건데, 또 로컬호스트에서만 돌아가는 프로젝트로 끝나는 게 싫어서 firebase hosting부터 붙이고 봤다.

다행히도 파이어베이스는 상당히 친절해서, 몇가지 질문을 통해 github actions를 이용한 CI/CD를 구성해줬다. 

이제 react app 코드를 잘 가져다가 보여줄 수 있도록 해야 하는데.. 이건 왜 안되는지 모르겠다. `<div id='root'></div>`만 추가해주면 될 줄 알았는데.

그리고 얼마전에 사놓고 묵혀둔 개인 도메인도 연결해보려고 했는데, 여기도 마음만 앞서서 일단 내 이름과 관련된 걸 구매하기만 했지 어떻게 쓰는지도 몰라서 이것도 알아봐야한다.

txt레코드를 등록해라 해서 뭔가 따라한 것 같은데, 적용에 시간이 걸리는건지 내가 제대로 하질 않은건지 연결이 안되는 듯 하다.

firebase hosting으로 리액트 앱 배포해본 사례 좀 찾아보고, 파이어베이스 호스팅 공식문서 좀 읽어보다보면 감이 잡히지 않을까 싶다.

새해엔 뭐라도 개인프로젝트를 끄적여야지.
