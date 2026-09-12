# Федоров Ярослав

**Frontend-разработчик** 

---

## Контактная информация

*   **Email:** yaroslav-fedor@mail.ru
*   **Местоположение:** Россия
*   **GitHub:** https://github.com/20yo0102
*   **Telegram:** @F_Y_A02
*   **Discord:** #20yo0102

---

## Опыт работы

### Фриланс
**Frontend разработчик** | 2025-2026

---

## Навыки

### Языки программирования
*   JavaScript (ES6+)

### Фреймворки и библиотеки
*   React
*   Node.js
*   Express.js
*   Bootstrap

### Инструменты
*   Git
*   Docker
*   Webpack
*   HTML
*   CSS
*   Agile/Scrum

### Языки
*   Английский язык (Upper-Intermediate)
*   Русский

 ### Пример кода `sortedSquares`

```javascript
var sortedSquares = function(nums) {
    const n = nums.length;
    const result = new Array(n); 
    
    let left = 0; 
    let right = n - 1; 
    let index = n - 1; 

    while (left <= right) {
        const leftSquare = nums[left] * nums[left];
        const rightSquare = nums[right] * nums[right];

        if (leftSquare > rightSquare) {
            result[index] = leftSquare;
            left++; 
        } else {
            result[index] = rightSquare;
            right--; 
        }
        index--; 
    }
    return result;
};
```


## О себе 
Мотивированный и целеустремленный разработчик с глубоким пониманием технологий. Стремлюсь применять свои навыки для создания инновационных и масштабируемых веб-приложений.
