# $isStreaming
desc
### Использование
```php
$isStreaming[userId?;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| userId | айди участника |  | Нет | 
| сервер | айди сервера |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$isStreaming',
  code: `
$isStreaming[userId?;сервер?]`
// Возвращает: логическое true/false
})
```
