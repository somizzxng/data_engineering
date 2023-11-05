```python
month_list = ["쌍", "쇠", "복", "돌", "팽", "육", "쌍", "개", "칠", "갑", "삼", "방"]

print(month_list)
```

    ['쌍', '쇠', '복', '돌', '팽', '육', '쌍', '개', '칠', '갑', '삼', '방']
    


```python
day_list = ["봉", "구", "욕", "포", "똥", "삼", "식", "석", "놈", "님", "년", "돌", "단", "득", "방", "질", "장", "걸", "래", "룡", "동", "순", "자", "박", "창", "언", "것", "포", "만", "단", "국"]

print(day_list)
```

    ['봉', '구', '욕', '포', '똥', '삼', '식', '석', '놈', '님', '년', '돌', '단', '득', '방', '질', '장', '걸', '래', '룡', '동', '순', '자', '박', '창', '언', '것', '포', '만', '단', '국']
    


```python
def get_my_chosun_name(family_name, month, day):

    month_name = month_list[month - 1]
    day_name = day_list[day - 1]
    
    chosun_name = family_name + month_name + day_name
    
    return f"당신의 조선시대 이름은 {chosun_name} 입니다."
```


```python
print(get_my_chosun_name('안', 9, 18))
```

    당신의 조선시대 이름은 안칠걸 입니다.
    
