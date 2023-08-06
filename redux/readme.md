# Redux Toolkit
  
# Advantages
 - Used for large-scale operation, big app, used it only required
 
 - zustand another library
 
 - easier to debug with extension using redux dev tool
 
 - redux and react are different library
 
 - 2 libraries - react-redux and redux toolkit


# Redux toolkit vs redux 

- Prevent writing lots of boiler code
- Prevent adding lot of packages to get Redux


- Redux is kept in a central place
- slices in redux store for different info like user theme display cart etc
- When we click on add button, it dispatch an action that calls reducer that modify cart slice in the redux store
- We use the selector to read data from the store which modify react component.
the phenomenon is called subscribing to the store

- npm install @redux/toolkit
- npm install react-redux

- Create a store using rtk Ex. appStore

- Wrap your component where you need redux using react-redux Provider
- Create slice using createSlice from rtk Ex. cartSlice 

		{
		name:'cart',
		initialState:{
		 item:[]},
		reducer:{
		
		addItem:(state,action)=>{
		}}}

- To Read store 
  the selector is hook useSelector() to access store,  import from react-redux

- dispatch action useDispatch hook from react-redux
