# useReducer 

- **local state management** 
- **Alternative to useState**
- We can use state obj and action obj
- We can have Multiple useReducer
- useReducer+useContext - used for global state management

# When to use useState vs useReducer

- number, string, boolean -**useState**
- array, object - **useReducer**

# Code 
    const initialState ={count:0}
    
    const reducer =(state, action){
      switch(action){
        case 'increment': return state+1
      }
    }

    const [count, dispatch] = useReducer(reducer, initialState)
    
    <button onClick={()=>{dispatch('increment')}}>
