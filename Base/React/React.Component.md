2022-06-04 23:51
Tags: #React
__
# React.Component
React позволяет определять компоненты как классы или функции. В настоящее время классовые компоненты имеют больше возможностей. Они разобраны на этой странице. Чтобы определить такой компонент, необходимо отнаследоваться от `React.Component`:

```jsx
class Component extends React.Component {
	return (
		<h1>Привет, {this.props.name}</h1>;
	)
}
```

Единственный _обязательный_ метод в подклассе `React.Component` — [`render()`](https://ru.reactjs.org/docs/react-component.html#render). Все остальные методы, описанные ниже, являются необязательными.
__
### Links
