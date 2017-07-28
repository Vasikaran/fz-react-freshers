#React Question Doubts
https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
###Shakil:
  **Question:**
  Parent has state. Child has state. Child state created using parent state inside constructor. When parent state changes. Its Not reflected child state.

  **Ans:**
    You have to handle using lifecycle method componentWillReceiveProps. Note: two set state happen but child render one time. More read the docs https://facebook.github.io/react/docs/react-component.html#componentwillreceiveprops

    Example under this folder libs/example1.html
