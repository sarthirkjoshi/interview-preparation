# React Storybook

# What & Why

- Development env and playground for UI components
- Create components independently
- Ability to view components that are already developed
- View what props it takes and change and try

- version 6  aug2020 V6
- npx sb init
- yarn storybook 
- Code
    export default {
    title:'Button',
    Componnent:Button
    }
    
    export const Primary =()=> <Button variant='primary'>Primary </Button>
    }
  
- Sorting, stories under story args
- decorator - components that wrap our story

- Addons  
  - docs  addon-docs
  - knobs addon-knob
  - actions (by default downloaded  with storybook )  addon-actions
  - viewport addon  addon-viewport
  - a11y addon 

-  Inject environment variables
- Build storybook - yarn build storybok  create storybook-static folder
