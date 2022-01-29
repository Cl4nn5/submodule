squash -> 찌그러트리다  
:과거로 찌그러뜨려야한다.

Index | 깃 메세지
---   | ---
0     | 로그인 퇴근
1     | 로그인 아픔
2     | 로그인 완료


0, 1을 합친다면 0을 `pick`하여 1로 `squash`하면 된다.
```
 git rebase -i HEAD ~ 3
```
  git rebase에 대한 기초를 알아야 merge --squash를 사용할 수 있다.