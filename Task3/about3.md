С этим заданием было посложнее, никак не мог понять заканомерность или неестественные детали, пока в один момент дошло что это очень сильно похоже на химические элементы...
и я был прав!

Простой код и у меня на руках интересная фраза!


```
# Химическая таблица элементов
periodic_table = {
    "Bk": 97, "Fl": 114, "Sb": 51, "Am": 95, "Ubu": None, "Cd": 48,
    "Ts": 117, "Mc": 115, "Md": 101, "Mt": 109, "Eu": 63
}

# Строка
input_str = "BkFlSbAmUbuCdTsAmMcMdMdAmMtMdEu"

# Разделение строки на потенциальные элементы
elements = ["Bk", "Fl", "Sb", "Am", "Ubu", "Cd", "Ts", "Am", "Mc", "Md", "Md", "Am", "Mt", "Md", "Eu"]

# Извлечение атомных номеров для известных элементов
atomic_numbers = [periodic_table.get(element, None) for element in elements]

atomic_numbers
```

ar3_0u_see_me?
