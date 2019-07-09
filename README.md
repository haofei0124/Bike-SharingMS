In this project mainly used React+AntDesign+LESS+Promise+axios+Echars  
  
1 technology stack and Component Library  
-------  
  
* AntDesign: UI library  
* LESS：  
* Promise that the data is immutable  
* Echarts： 
* axios： AJAX  
  
2 Architecture description  
-------  
  
>┣━ build   // Package file   
>┣━ public   // Package file  
>>┣━ assets   // marker pics  
>>┣━ carousel-img   // carousel imgs  
>>┣━ gallery   // gallery imgs   
>┣━ src //Development directory  
>>┣━ axios   // JsonP and AJAX  
>>┣━ components   // Header, Footer and NavLeft components   
>>┣━ config   // for NavLeft data  
>>┣━ pages   // pages  
>>>┣━ city  // city control  
>>>┣━ echarts   // echarts use  
>>>┣━ form   // form   
>>>>┣━ login.js   // login form  
>>>>┣━ register.js   // register form  
>>>┣━ home   // home page  
>>>┣━ login   // login page  
>>>┣━ nomatch // no match 404 page  
>>>┣━ order   // order control  
>>>┣━ rich    // rich text  
>>>┣━ table   // table  
>>>┣━ ui  
>>>>┣━ buttons.js     
>>>>┣━ carousel.js  
>>>>┣━ gallery.js   
>>>>┣━ loadings.js  
>>>>┣━ messages.js    
>>>>┣━ modals.js  
>>>>┣━ motice.js  
>>>>┣━ tabs.js    
>>>>┣━ ui.css  
>>>>┣━ ui.less  
>>>┣━ user  // user control    
>>┣━ resource  
>>┣━ style  //Global style  
>>┣━ utils // pagination and Date  
>>┣━ admin.js  // UI layout  
>>┣━ App.js   //entry and router  
>>┣━ common.js   //  
>>┣━ index.js   //  
>>┣━ router.js  //  
>┣━ package.json  
>┣━ README.md  
>┣━ yarn.lock  
  
3 Achieve some functions    
-------  
  
* Deep understood and use AntDesign to implement function from AntD  
  
* check order detail on map  
  
* Add city and user  
  
* Echarts show information  
  
4 Operation of development environment  
-------  
  
Install dependencies:  
  * npm install  
  
Run project, run it on: localhost:3000  
  * npm run start  
  * yarn start  
  