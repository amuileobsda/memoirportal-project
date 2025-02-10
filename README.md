# memoirportal-project
## 목차 | Contents
1️⃣ [기획의도](#기획의도) <br/>
2️⃣ [프로젝트 소개](#프로젝트-소개) <br/>
3️⃣ [아키텍처](#아키텍처) <br/>
4️⃣ [리눅스 LAMPN서버 구축 및 과정](#리눅스-LAMPN서버-구축-및-과정) <br/>
5️⃣ [사이트 경로](#사이트-경로) <br/>
6️⃣ [기술 스택](#기술-스택) <br/>
7️⃣ [프로젝트 방향성](#프로젝트-방향성) <br/>


## 기획의도
우리는 모두 각자의 삶에서 소중한 순간들을 경험하고, 그 순간들을 기억 속에 간직하고 싶어 합니다. 

하지만 시간이 지나면 그 기억들은 점차 흐려지고, 쉽게 잊혀지기도 합니다. 

저는 이러한 기억들을 기록하고, 언제든지 다시 찾아볼 수 있는 개인적인 공간을 만들고 싶었습니다.


## 프로젝트 소개
저는 웹사이트 방문자의 데이터를 활용하여 웹사이트의 성과를 분석하는 툴인 Google Analytics에서 영감을 받았습니다. 

이런 방식은 사이트가 어떻게 운영되고 있는지를 실시간으로 파악하고, 더 나은 방향으로 개선해 나가는 데 도움을 줍니다.

이를 바탕으로, MemoirPortal.com을 개발하게 되었습니다. 

이 플랫폼은 사용자가 자신이 작성한 글을 쉽게 기록하고 관리할 수 있도록 돕는 서비스입니다. 

사용자는 각자의 블로그 포스트를 통합된 페이지에서 편리하게 확인하고, 다양한 스타일로 콘텐츠를 작성하며 그들의 기억을 남길 수 있습니다.

MemoirPortal의 UI는 Microsoft Edge에서 영감을 받아, 깔끔하고 직관적인 디자인을 제공합니다. 

사용자는 언제든지 자신의 글을 수정하거나 업데이트할 수 있으며, 전체 페이지는 쉽게 탐색할 수 있도록 구성되었습니다. 

또한, 블로그 디자인과 기능을 개인화할 수 있어, 자신만의 고유한 공간을 만들 수 있습니다.


## 아키텍처
<img width="800" alt="아키텍쳐_초기" src="https://github.com/amuileobsda/data-visualization-project/assets/30142355/c88a243e-f154-4313-baff-c311052e9d35">

## 리눅스 LAMPN서버 구축 및 과정
1) 서버에 Linux, Apache, Mysql, php, node.js 설치
2) certbot을 이용한 SSL 인증서 적용
3) 방화벽 설정
4) 포트추가
5) IP주소 필터링
6) 도메인 및 서브도메인 적용
7) 아파치 웹서버에 node서버추가


## 사이트 경로
| 설명                      | 경로                                                                          | 접근        |
| ------------------------- | ----------------------------------------------------------------------------- | ----------- |
| 통합포탈 사이트 경로        | [https://www.memoirportal.com/](https://www.memoirportal.com/)                 | O          |
| 개인포탈 경로              | [https://www.memoirportal.com/knowledge/@llo2091](https://www.memoirportal.com/knowledge/@llo2091)   | O          |
| 개인포탈 경로              | [https://www.memoirportal.com/knowledge/@oko2092](https://www.memoirportal.com/knowledge/@oko2092)   | O          |
| 포탈 로그인 경로           | [http://www.memoirportal.com/admin/](https://www.memoirportal.com/admin/login.php) | O          |
| 아이디 / 패스워드          | llo2091 / test1234                                                                 |            |
| 아이디 / 패스워드           | oko2092 / test1234                                                                |            |


## 기술 스택
- PHP, Redis, Javascript, Jquery, MySQL, Apache, CentOS


## 프로젝트 방향성
<table>
  <tbody>
    <tr>
      <td>AWS를 사용안한 이유</td>
      <td>비용 <br/>AWS는 유연한 서비스와 확장성을 제공하지만, 사용량에 따라 비용이 증가할 수 있습니다.</td>
    </tr>
  </tbody>
</table>
