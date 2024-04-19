# Markdown 연습하기

일반 문장 또는 문단을 표현할때는 그냥 적으시면 됩니다.

## 점심메뉴

- 김치찌개
- 된장찌개
- 순두부 찌개

## 8월 여행 가고싶은 곳 순위

1. 일본
2. 대만
3. 미국
4. 호주

### python으로 인사하는 법 
```python
def hello(name: str, country='kr':str) -> str:
    """
    국적에 맞게 인사합니다.
    사용자는 본인의 일므과 국적을 argument로 전달해야 합니다.
    """

    if country.lower() == 'kr':
        greeting = f"안녕하세요, {name}님"

    return greeting
```

문장속에서 어떤 부분을 `강조` 하려면 `backquote`를 감싸면 됩니다.

### Reference

-[Google](https://www.google.com/)
![고양이](./cat.jpg)

## vim mode

- Normal mode : default, press esc on any mode
- insert mode : press `i` on Normal mode
- visual mode : press `v` on Normal mode
- command mode : press on `:` Normal mode




