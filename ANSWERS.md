- [ ] Why would you use class component over function components (removing hooks from the question)?

    You use class components over function components in order to create more dynamic interactions and thus it's better if you needed to utilize state or a lifecycle method.

- [ ] Name three lifecycle methods and their purposes.

    1. componentDidMount: This is the phase where the component takes birth, render method is invoked.
    2. componentDidUpdate: This is the growth phase of the component set state can be used at this stage and API calls can be made, shouldComponentUpdate method can be used at this stage to stop the component from rendering.
    3. componentWillUnmount: This is the death phase of the component, component is removed from the screen and its life cycle is ended.

- [ ] What is the purpose of a custom hook?

    Custom hooks allow you to write a function that holds stateful logic once and reuse it throughout your code. Keeping code DRY and more readable.

- [ ] Why is it important to test our apps?

    It is important to test apps because it helps us write cleaner, better code. Provides a safety net so someone doesn't come in later and break the code. It allows for easier code maintenance as well. 