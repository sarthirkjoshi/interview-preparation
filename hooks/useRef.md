# useRef hook
- It creates mutable elements which will not rerender the component.
- to access DOM element directly
- usecase1 - focus text input 
- used to store any mutable value
- prevents rerendering

- Code: 

    const inputRef = useRef(null)
    
    useEffect(()=>{
    inputRef. current. focus()
    },[])
    
   input ref={inputRef} 
