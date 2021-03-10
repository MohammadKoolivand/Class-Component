# Class-Component

## Deffinition
React has ability to operate with reusable components. React component are two types of **Class Component** & **Function Copmonent**. Here we are focusing on Class Components.

## Creating a Class Component
creating a class component has some steps to do:
1. every class component must start with an upper case letter.
2. every component must include **`extends React.Component`**. This gets inheritance to the component.
3. components must have **`render()`** method also. This method returns an HTML tag

## Class Component Sample

```js
class Welcome extends React.Component {
  render() {
    return <h1>Hello, {this.props.name}</h1>;
  }
}
```
## Class Components Lifecycle
![dom](https://user-images.githubusercontent.com/48600357/110586113-e4410800-8186-11eb-9a2e-9544ced53a0e.png)

