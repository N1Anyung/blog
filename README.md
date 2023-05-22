
# Документация

Документация проекта Blog


## Технологии

**Клиент:** HTML, CSS, JS

**Зависимости**: font-awesome@6.4.0




## Переменные

#### Все динамические переменные хранятся в ``LocalStorage``


```bash
  token - токен авторизованности
```
```bash
  users - список зарегистрированных пользователей
```
```bash
  currentUser - авторизованный на данный моммент пользователь
```
```bash
  posts - список постов
```
  Объект post имеет вид
```bash   
{
  content: '' ,   // 'testcontent'
  actions: {
      like: 0,
      dislike: 0,
  },
  likedBy: [],    // ['login1', 'login2']
  dislikedBy: [], // ['login1', 'login2']
  comments: [],
  author: 'currentUser'
}
```

```bash
  comments - список комментариев
```
  Объект comment имеет вид
```bash   
{
  author: 'currentUser',
  text: '', // 'текстовый контент комментария'
  time: 'время'
}
```
## Функции

Функция для обработки авторизации и существующих постов и их отображения
```bash
  load() 
```

Функция для отображения об отсутствии постов
```bash
  noPost()
```

Функция для создания аккаунта
```bash
  register()
```

Функция для входа в аккаунта
```bash
  logout()
```

Функция для выхода из аккаунта
```bash
  logout()
```

Функция для создания поста
```bash
  save()
```

