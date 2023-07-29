# useEffect

- To perform side effects in functional component
- Replacement of **componentDidMount**, **componentDidUpdate** and **componentWillUnmount**
- useEffect **runs after every render** of the component.
- You can mimic **componentDidMount** by passing an **empty** dependency array in useEffect
- Cleanup activity can be done with returning from useEffect.

      Ex.
      useEffect(()=>{
      return()=>{
      window.removeEventListener('mousemove', position)
      }
      })

- We can add **multiple** useEffect in one functional component

- Fetch api in useEffect using axios or fetch 
