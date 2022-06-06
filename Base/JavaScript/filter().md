2022-06-05 20:31
Tags: #JavaScript #Array
__
# filter()
На тот случай, если найденных элементов может быть много, предусмотрен метод `arr.filter(fn)`.

Синтаксис этого метода схож с `find`, но `filter` возвращает массив из всех подходящих элементов:
```js
let results = arr.filter(function(item, index, array) {
//item - элемент массива
//index - индекс массива
//array - сам массив
// если true - элемент добавляется к результату, и перебор продолжается
// возвращается пустой массив в случае, если ничего не найдено });
```

Например:
```js
let users = [
	{id: 1, name: "Вася"},
	{id: 2, name: "Петя"},
	{id: 3, name: "Маша"}
]; 

// возвращает массив, состоящий из двух первых пользователей
let someUsers = users.filter(item => item.id < 3);

alert(someUsers.length); // 2

arr.filter( el => typeOf el === 'number') // сортировка по типу
```

__
### Links
[[Методы массива]]