## Project overview
Firebase 기반으로 백엔드를 구성하며,  
프론트엔드는 react 및 shadcn/ui 라이브러리를 활용하여 현대적이고 깔끔한 UI/UX를 제공합니다.

## Core functionalities

2.1 사용자 인증  
- firebase Authentication 기능을 사용합니다.  
- google 계정 로그인 연동  
- 이메일/비밀번호 로그인 기능 구현  

2.2 사용자 프로필  
- firebase storage를 활용한 프로필 이미지 업로드 및 수정 기능  
- firestore에 사용자 정보를 저장합니다 (이메일, 닉네임, 가입일자, 이미지 uri 등 필요한 정보)  

2.3 게시글 시스템  
- 글 작성, 수정, 삭제 기능  
- 전체 글 목록 조회 및 정렬 (최신, 인기순)  
- 게시글 상세 페이지 구현  
- firestore를 활용한 데이터 저장 및 쿼리  

2.4 댓글 시스템  
- firestore 서브컬렉션을 활용하여 게시글별 댓글 저장  
- 댓글 작성, 수정, 삭제 기능  
- 실시간 업데이트 기능  

2.5 좋아요 및 북마크 기능  
- firestore의 유저 id 기준으로 좋아요 및 북마크 기록을 저장합니다.  
- 좋아요/북마크 기준 조회 기능  
- 각 게시물의 좋아요 수, 북마크 수 표시  

2.6 1대1 채팅 기능  
- firebase realtime database 사용  
- 유저간 1대1 대화방 생성 및 실시간 메시지 송수신  
- 채팅 UI (이모션 입력과 미리보기, 타임스탬프, 읽음 알림을 확인)  

2.7 반응형 UI 및 디자인 시스템  
- shadcn/ui 컴포넌트  
- tailwindcss 기반으로 커스텀 테마 적용  
- 다크/라이트 모드 기능 구현  
- 모바일/태블릿/데스크탑 반응형 최적화  

2.8 배포  
- firebase hosting

# Doc

- 프론트엔드 : react, typescript, tailwindCSS, shadcn/ui
- 백엔드 : firebase (Auth, firestore, realtime DB, Storage, hosting)
-

# Current file structure