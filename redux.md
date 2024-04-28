### React & Redux Evaluation Test
#### Part 1: Theoretical Knowledge

## 1. Explain the core concepts of React and Redux.
Ans:-
     1.React:-React is a free and open-source front-end javascript llibarary for building user interfaces basrd on componants.and created by facebook.
     React is a javascript libarary for building user interface.
     it ia used to build  single page applications.its allows us to create reusable Ui componant.


        
     2.Redux:-
        The core concept of redux is 
         (1).Entire state of your applications is stored in a js object called "Store"
            
            Store:-the store source of trith that hold entire state of the application.

            import {createStore} from "redux"

            const store =createStore(counter,action);


         (2).Action:- plain javascript object decribing what happend in the application.
         export const Counter=(count)=>{
            {
                type:IncreseData,
                payload:{count}
            }
         }

         (3).reducers:-Function that specify how to the application state changes in response to action.
         const initialState={

         }
         const rootReducer=(state=initialState,action)=>{
            return state.
         }

## 2. Differentiate between React's functional components and class components.
   1.class components:-
   (a)class component is apply both options for use the props and set the state also.
   (2)class components also known as statefull components contain stat and lifecycle methods and are written with javascript es6 classes.
     
   2functional components:-
    (a)functional component only accept the props as an arguments.
    (b)functional component are a simple ,fast and easy way to design and develop a component in react.they are used tyo create components that return jsx and don't have theur sate.

## 4. What is the purpose of the Redux store? How does it differ from React's local component state?

Ans:-
    Entire state of your applications is stored in a js object called "Store"
            
            Store:-the store source of trith that hold entire state of the application.

            import {createStore} from "redux"

            const store =createStore(counter,action);

      differ from React's local component state:--
      Redux store is the data store is your create Application .
      And  React's local component state is data store your Webrowser like crome ,brave...
      



## 6. Describe the role of actions and reducers in Redux. Provide an example of how they work together.

Ans:-Action:- plain javascript object decribing what happend in the application.
         export const Counter=(count)=>{
            {
                type:IncreseData,
                payload:{count}
            }
         }

         reducers:-Function that specify how to the application state changes in response to action.
         const initialState={

         }
         const rootReducer=(state=initialState,action)=>{
            return state.
         }

## 7. What is the purpose of React Router? How does it facilitate navigation in a React application?
    
    react router of purpose is collection of navigational component and tools that allows you to create single page application with multiple views pages.
     
     react-router-dom is package that provides routing functionalty for react applications.

     install:- npm i react-router-dom 
      fristly App.js ko BrowserRouter ya Router se raip karenge.

      <BrowserRouter>
          </App>
      </<BrowserRouter>>

      <Routes>
           <Route path="/" element={</Home>}/>
            <Route path="cart" element={</Cart>}/>
             <Route path="*" element={</Contact>}/>

       </Routes>     
   ** Default Route for the parent route which is / and * is for any undefined Urls.
   .

   ## 8. Discuss the significance of React Hooks and provide examples of commonly used hooks.

     React Hooks:-Hooks allows to functional components to have access to state and other features.Because of this ,class components are generally no longer needed.

     There are 3 rules for hooks.
        (a)Hooks can only be called inside react function components.
        (b)Hooks can only be called at the top level of a component.
        (c)Hooks connot be conditional.

        Hooks of list

     useState()
     useEffect()
     useContext()
     useMemo()
     useReducer()
     useRef()
     useCallback()



#### 4. You have 30 minutes to complete the test.


**2. What are the main components of the CSS box model? Briefly describe each component.**

A css box model consists of some of boxes wrapped around an HTMl element for styling pusposes.

there are four makes of box model:-
margin box
padding box
content box
border box

 content:- The content of the box where text and images appear.

  padding:- Clears an area around the content.the padding is transparent.

  border:-A border is the around the padding and content.

  Margin:- Clears an area outeside the border.the margin is transparent.


 **3. Explain the difference between content, padding, border, and margin in CSS.**
  
  content:- The content of the box where text and images appear.

  padding:- Clears an area around the content.the padding is transparent.

  border:-A border is the around the padding and content.

  Margin:- Clears an area outeside the border.the margin is transparent.

##  4. How can you change the size of an HTML element using CSS properties related to the box
  ## model? Provide examples.**
  Ans:-1. the css height and width properties are used to set height and width of an element.
       2.max-width property is used the to set the maxmimum width of an element.

## **5. Write a CSS rule to set the padding of a `div` element to 20 pixels on all sides.**
   The css rule to set the padding of a div element to -  padding:20px;
                                                          padding:20px 20px;
                                                          padding:auto;

## **6. Describe the differences between `margin` and `padding` in CSS. When would you use one over the other?*                                                         
   ans:- Margin: Clears an area outeside the border.the margin is transparent.
       margin:20px;
       margin:20px 20px;                                      
       margin:auto;
       margin-left:10px;
       margin-right:10px;
       margin-bottom:10px;
       margin-top:10px;
   
  padding:- Clears an area around the content.the padding is transparent.
       padding:20px;
       padding:20px 20px;                                      
       padding:auto;
       padding-left:10px;
       padding-right:10px;
       padding-bottom:10px;
       padding-top:10px;