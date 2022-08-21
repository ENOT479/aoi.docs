# $writeFile
записывает определенную информацию в файл
### Использование
```php
$writeFile[file;text;encode?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| file | файл в который будет записана информация |  | Да | 
| text | текст который будет записан в файл |  | Да | 
| encode |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$writeFile',
  code: `
$writeFile[file.txt;weredokGang]`
// Возвращает: WeredokGang
})
```
