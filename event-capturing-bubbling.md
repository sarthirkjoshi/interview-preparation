**Event Propagation**

- Determines in which order the element receives and event.

**Event bubbling**

- In this the events are propagated from **inner child to outer parent**
- This is the **default behvaiour**
  

**Event capturing**

- In this the events are propagated from **outer parent to innermost child**
  

  **event.stopPropagation()** - It prevents calling next event in queue.


**MOST IMPORTANT - How to make any even to work as Event Capturing**

- passing 3rd argument **true** to **addEvenetListerner** will make your event to function as  **event capturing**

parentCall(){alert('Parent div called')} 
childCall(){alert('Child div called')}

parentId.addEvenetListerner('click',parentCall,true)
parentId.addEvenetListerner('click',childCall,true)
  

![image](https://github.com/sarthirkjoshi/interview-preparation/assets/46737879/f9ec1a3d-4f6f-488a-9b5f-30e925bcdd98)
