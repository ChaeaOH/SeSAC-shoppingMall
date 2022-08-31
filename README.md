# 💻Project

SeSAC 산업진흥원 프론트엔드 실무 교육과정에서 **REACT를 기반으로 한 쇼핑몰**의 기본 기능을 구현하였습니다.

# 🌲Structure Tree
src  
 ┣ components  
 ┃ ┣ CartItem.css  
 ┃ ┣ CartItem.js  
 ┃ ┣ CartList.css  
 ┃ ┣ CartList.js  
 ┃ ┣ Detail.js  
 ┃ ┣ Login.js  
 ┃ ┣ Nav.css  
 ┃ ┣ Nav.js  
 ┃ ┣ ProductItem.css  
 ┃ ┣ ProductItem.js  
 ┃ ┣ ProductList.css  
 ┃ ┗ ProductList.js  
 ┣ route  
 ┃ ┗ UserRedirects.js  
 ┣ store  
 ┃ ┣ cart  
 ┃ ┃ ┗ cartSlice.js  
 ┃ ┣ user  
 ┃ ┃ ┗ userSlice.js  
 ┃ ┗ index.js  
 ┣ App.css  
 ┣ App.js
# 🔍Detail
1. 간단한 로그인기능을 구현하여 로그인 시 상세페이지에  접근가능하고 로그아웃시 Redirect되도록 **UserRedirects 컴포넌트**를 만들었습니다.
2. 장바구니 추가를 눌렀을 때 장바구니에 넣은 상품을 유지시키고, 동일한 상품이 장바구니에 담겼을 경우 알림창을 띄울 수 있도록 **Redux-Toolkit과 persist**를 사용했습니다.
3. 각 상세페이지 URL 접속시 상품명,내용,가격등을 다르게 보여줘야 하므로 Json 가상 데이터 안에 있는 id,title 등을 쓸 수 있도록  **useParams**라는 훅을 사용했습니다.

# 🚀Result
<img width="{80%}" src="https://ndb796.tistory.com/557 [안경잡이개발자:티스토리](https://mail.google.com/mail/u/0?ui=2&ik=8e653972e2&attid=0.1&permmsgid=msg-a:r8212590978466731852&th=182f25297a2051ca&view=fimg&fur=ip&sz=s0-l75-ft&attbid=ANGjdJ_bNkA5bGiV6hDVVIRA_FlJEuWM2rX5-QI03zsK75q9wcLhO8guShLxE2UsC82ZosJtRJmGXcOhU3VDiP6-iASHBW3aUI9zOAeDu4tA5VC_2ZsX5sW4QpRo41g&disp=emb&realattid=ii_l7h5xuzl0)"/>

# 💡Review

 - **Redux-Toolkit** 에서 제공하는 주요 함수들을 사용하면 기존 Redux의 복잡도를 낮추고 사용성을 높여서 코드를 작성할 수 있다는 것을 경험했습니다.
- createSlice 함수를 사용하여 slice를 작성하면 기존의 Redux로 reducer를 구성했을 때 비해서 코드가 많이 줄어든 것을 확인했습니다.
- 아직 Redux-Toolkit 에서 제공하는 주요 함수들이나 용어들이 익숙하지 않지만 앞으로 프로젝트를 진행할 때마다 데이터 관리와 상태 관리가 가장 중요하기 때문에 더 깊은 학습 필요성을 느꼈습니다.

