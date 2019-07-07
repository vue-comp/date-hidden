# date-hidden
Компонент для работы с Vuetify компонентом v-date-picker для скрытия/показа date-picker. Имеет возможность ручного ввода в v-text-field с маской ##.##.####

--------------------------
Установка: npm i date-hidden

--------------------------
Использование

Импорт компонента: 
```javascript  
import dateHidden from 'date-hidden'
```
Регистрация компонента:
```javascript 
export default {
    components: {
        'date-hidden': dateHidden,
    } 
```
Пример использования: 
```html 
<date-hidden label="Some label" @change-date="someDate=$event"></date-hidden> 
```

---------------------------
Дополнительные необзяательные props

1. color - установка цвета. По умолчанию: 'primary'
2. readonly - отмена возможности ручнного ввода. По умолчанию: false
3. required - обязательность поля. По умолчанию: false

----------------------------
Дополнительно

PS: для корректной работы компонента, необходимо использовать Vue-cli