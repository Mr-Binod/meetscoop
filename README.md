

# meetscoop



## 목차
- [프로젝트 소개](#프로젝트-소개)
- [팀원 소개](#팀원-소개)
- [화면 구성](#화면-구성)
- [주요 기능](#주요-기능)
- [개발 기간](#개발-기간)
- [기술 스택](#기술-스택)
- [협업 도구](#협업-도구-communication)
- [폴더 구조](#폴더-구조)

## 프로젝트 소개
meetscoop는 도호회 회원들의 적극적인 참여를 통해 협력과 성장을 도모하는 것을 목표로 합니다. 성공적인 동호회 프로젝트 사례를 참고하여 기대 요과와 구체적인 결과물을 제시합니다.

---

## 팀원 소개 
<div>
<img src="https://github.com/Mr-Binod.png" width="80px"><br>
<a href="https://github.com/Mr-Binod">팀원 : 비노드 </a><br>
역활활 : 로그인 페이지, 마이 페이지
</div><br>

<div>
<img src="https://github.com/susuholee.png" width="80px"><br>
<a href="https://github.com/susuholee">팀원 : 이수호 </a><br>
역활 : 메인 페이지
</div><br>

<div>
<img src="https://github.com/zzeen2.png" width="80px"><br>
<a href="https://github.com/zzeen2">팀원 : 깁지은 </a><br>
역활 : 도호회 페이지, 추가 페이지, 상세 페이지
</div>


## 화면 구성 :
<label>카카오 로그인</label>
<img src="./public/images/gif/kakaologinscoop-ezgif.com-speed.gif"><br><br>
<label>개인 정보 수정</label>
<img src="./public/images/gif/mypagedetails-ezgif.com-video-to-gif-converter.gif"><br><br>
<label>마이 페이지 기능</label>
<img src="./public/images/gif/personaldetaileditscoop-ezgif.com-speed.gif">
## 주요 기능: 

### 담당 : 로그인 페이지
- 카카오 인증 사용해서 로그인 페이지 구현
- 로그인할때 카카오 로그인 화면을 보이고 아이디와 비밀번호를 작성후 카카오에서 인증 받고 쿠키저장하여 로그인 완료 기능
- 해더바에 로그인 버턴 생기고 로그인 완료후 회원 사진, 닉네임랑 로그아웃버턴 생김

### 담당 : 마이 페이지
- 회원 정보 확인 및 수정 기능
- 포인트 350 가진 회원들이 동호회 추가하기 버턴 생기고 동오회 추가할수있는 기능
- 본인이 생성한 동호회 페이지를 확인
- 본인이 좋아요나 댓글 다르는 돟호회 페이지를 확인 그리고 사진 누루면 상세 페이지 이동
- 나의 달력에서 참여 이벤트 날짜랑 내용을 확인 가능 


## 개발 기간
- 2025-05-16 ~ 2025-06-1 (16일)


## API 문서 

<table> <tr> <th>Method</th> <th>Route</th> <th>Description</th> </tr> <tr> <td>GET</td> <td>/login</td> <td>로그인 페이지</td> </tr> <tr> <td>GET</td> <td>/kakao/login</td> <td>카카오 로그인 화면 페이지</td> </tr> <tr> <td>GET</td> <td>/auth/kakao/callback</td> <td>카카오 로그인 인증받고 쿠키 생성후 로그인 완료</td> </tr> <tr> <td>GET</td> <td>/mypage</td> <td>마이 페이지 이동</td> </tr> <tr> <td>GET</td> <td>/logout</td> <td>로그아웃 화면 이동</td> </tr> <tr> <td>GET</td> <td>/auth/kakao/logout/callback</td> <td>쿠키 삭제후 로그아웃 메인 페이지 이동</td> </tr> <tr> <td>GET</td> <td>/Edituser</td> <td>유저 정보 수정 페이지</td> </tr> <tr> <td>GET</td> <td>/checkcookie</td> <td>쿠키 확인</td> </tr>  </table>

<table> <tr> <th>Method</th> <th>Route</th> <th>Description</th> </tr> <tr> <td>POST</td> <td>/Edituser</td> <td>유저 정보 수정</td> </tr> </table>


## 기술 스택 
### FRONTEND

<table>
  <tr>
    <td align="center">
      <img src="./public/techstack/html-5_5968267.png" width="200px"><br>
      <label>HTML5</label>
    </td>
    <td align="center">
      <img src="./public/techstack/css.png" width="200px"><br>
      <label>CSS</label>
    </td>
    <td align="center">
      <img src="./public/techstack/js_5968292.png" width="200px"><br>
      <label>JavaScript</label>
    </td>
  </tr>
</table>

### BACKEND
<table>
  <tr>
    <td align="center">
      <img src="./public/techstack/js_5968292.png" width="200px"><br>
      <label>JavaScript</label>
    </td>
    <td align="center">
      <img src="./public/techstack/mysql.png" width="200px"><br>
      <label>MySQL</label>
    </td>
    <td align="center">
      <img src="./public/techstack/nodejs.256x157.png" width="200px"><br>
      <label>Node.js</label>
    </td>
  </tr>
</table>

### API
<table>
  <tr>
    <td align="center">
      <img src="./public/techstack/kakao.png" width="200px"><br>
      <label>Kakao</label>
    </td>
    <td align="center">
      <img src="./public/techstack/kakaomap.png" width="200px"><br>
      <label>Kakao Map</label>
    </td>
  </tr>
</table>

### 협업 도구 COMMUNICATION 
<table>
  <tr>
    <td align="center">
      <img src="./public/techstack/Notion.png" width="200px"><br>
      <label>Notion</label>
    </td>
    <td align="center">
      <img src="./public/techstack/github_2504911.png" width="200px"><br>
      <label>GitHub</label>
    </td>
  </tr>
</table>



## 폴더 구조
### 프론트 폴더 구조
---
📦meetscoop

┣ 📂 controllers

┣ 📂 json

┣ 📂 lib

┣ 📂 models

┣ 📂 public

┣ 📂 routers

┣ 📂 views

┣ 📜 server.js

┣ 📜 README.md

┣ 📜 package-lock.json

┣ 📜 package.json


