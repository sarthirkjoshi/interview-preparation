# useContext 

- First 2 steps are the same in context API and useContent. Only the consumption part is different.

# Step 1 - Create Context

    export const ChannelContext= React.createContext()

# Step2- Wrap component and pass value 

    <ChannelContext.Provider value={'Shaurya'}>
    <ComponentB>
    </ChannelContext.Provider>

# Step3- import context and use useContext hook


    import {useContext} from 'react'
    import {ChannelContext} from '/app'
    
    const channel = useContext(ChannelContext)
    
    <h1>{channel}</h1>
