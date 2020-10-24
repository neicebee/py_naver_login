# py_naver_login
bvsd를 이용해 captcha를 무력화시키는 네이버 자동 로그인 라이브러리⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀

## 사용예시
from pynaverlogin import n_login

  a = n_login.n_login(id, pw)
  
with a.get_session(id, pw) as s:

  print(s.get("https://www.naver.com"))

=> a.get_session() method : return type <class 'requests.sessions.Session'>
