2022-06-05 00:08
Tags: #
__
# findDOMNode()
```
ReactDOM.findDOMNode(component)
```

Если этот компонент был смонтирован в DOM, он возвращает соответствующий DOM-элемент браузера. Этот метод полезен для чтения напрямую из DOM (например, чтение значений полей формы) или произведения измерений DOM. **В большинстве случаев, вы можете присоединить реф к узлу DOM и полностью избежать использования `findDOMNode`.**

Когда компонент рендерится в `null` или `false`, `findDOMNode` возвращает `null`. Когда компонент рендерится в строку, `findDOMNode` возвращает текстовый узел DOM, содержащий это значение. Начиная с React 16, компонент может возвращать фрагмент с несколькими дочерними элементами, и в этом случае `findDOMNode` возвращает DOM-узел, соответствующий первому непустому дочернему элементу.
__
### Links
[[ReactDOM]]