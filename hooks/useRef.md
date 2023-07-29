# useRef hook

- usecase1 - focus text input 
- used to store any mutable value
- prevents rerendering

- Code: 

    const inputRef = useRef(null)
    
    useEffect(()=>{
    inputRef. current. focus()
    },[])
    
   input ref={inputRef} 
