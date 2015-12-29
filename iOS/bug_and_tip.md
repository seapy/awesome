# 버그 & 팁

애플이 고쳐주지 않는 버그로 인해 고생하는 개발자들 ㅜㅜ 또 버그는 아니더라도 꼼수들 모음

## UITextView

- 텍스트를 변경해도 이전 텍스트의 링크가 남아 있는 버그
  - 아래 방법으로 꼼수를 쓰면 된다. [링크](http://stackoverflow.com/a/25994821/397457)
```
textView.text = nil
textView.text = "​\u{200B}\(newText)"
```
- 텍스트에 링크같은건 터치가능하게 하고 싶지만 선택하는건 원치 않는경우
  - iOS 8.4에서는 되지만 9에서는 안되는 방법 [링크](http://stackoverflow.com/a/27264999/397457)
