**CSS Position**

- **Five** position properties - **static, relative, absolute, fixed and sticky**

 1. **static**
     - default property for position
     
       `position:static`


 2. **relative**
    
     - Allows you change the poition relative to where it is present
     - it removes element out of the docuemnt flow when given top,left,right, up and down so **not recommented** to use top left with relative.
     
        `position:relative`

 3. **absolute**
    
     - completely removes element from document flow and it doesnt exist and **other element ignores it completely**
     - When you want to add top,left,right,bottom, you need to give **parent relative position** so that it works fine 
     
          `position:absolute;
           top:10px;botton:5px;left:5px;right:2px;
           
          `


 5.  **fixed**

      - completely ignores document and it sticks to particular place.
      - It **moves with the scroll** , it is there though anyone scrol down.
        

         `position:fixed; top:0`

 6.  **sticky**
    
     - **Combination of relative and fixed position into one**
     
         `position:sticky;
          top:0`
