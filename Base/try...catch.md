2022-07-19 15:53
Tags: #
__
# try...catch

Конструкция `try...catch` пытается выполнить инструкции в блоке `try`, и, в случае ошибки, выполняет блок `catch`.

```js
try {
   _try_statements_
}
[catch (_exception_var_1_ if _condition_1_) { // не стандартно
   _catch_statements_1_
}]
...
[catch (_exception_var_2_) {
   _catch_statements_2_
}]
[finally {
   _finally_statements_
}]
```
`try_statements` - инструкции для выполнения.
`catch_statements_1` - инструкции, будут выполнены, если будет ошибка в блоке `try`.
`exception_var_1` - хранение объекта ошибки, который используется в `catch`
`condition_1` - условное выражение.
`finally_statements` - инструкции, которые выполняются после завершения блока `try`. Выполнение происходит в независимости от того, произошла ошибка или нет.

## Описание
Конструкция `try` содержит блок `try`, в котором находится одна или несколько инструкций (Блок (`{}` ) обязательно должен присутствовать, даже если выполняется всего одна инструкция), и хотя бы один блок `catch` или `finally`. Таким образом, есть три основные формы конструкции `try`:
1.  `try {...} catch {...}`
2.  `try {...} finally {...}`
3.  `try {...} catch {...} finally {...}`

__
### Links