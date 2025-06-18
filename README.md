# Namaste React

# parcel
-Dev Build

-Local Server

-HMR-Hot Module Replacement:HMR stands for Hot Module Replacement — a feature that allows instant updates in the browser without refreshing the entire page when you save a file.

-File Watching Algorithm -written in C++

-Parcel is a fast, zero-config web development tool that allows you to build, serve, and
optimize your web applications with ease.

-Image Optimization

-Minification

-Bundling

-Compressing

-consistant Hashing

-Code Splitting

-Differential Bundling -Support Older Browser

-Diagnostic

-Error Handling

-HTTPs

-Tree Shaking

-Different Dev and Production Bundles

-Babel => It transpiles the JSX code into React code

-Components => Class Based component
            => Functional Based Component


-Two Types Of Exports/Import
            =>Default Export/Import
            =>Named Export/Import

   # React Hooks
            =>usestate()
            =>useffect()         
  # File Path
  =>cd D:\Namaste-React\React

  #  React Router Dom

  =>createBrowserRouter
  =>RouterProvider

  # 2 type Routing in web pages 
  
    => Client Side Routing
    => Server Side Routing 

   # State Variable
    =>Never Update State variable directly [For ex. onclick={()=>{
      this.state.count= this.state.count+1
    }
    }]
    => do it with(this.setstate())

  # Life cycle of React component 
  
  1. Parent constructor()
  2. Parent getDerivedStateFromProps()
  3. Parent render()
   ⤷ 4. Child constructor()
   ⤷ 5. Child getDerivedStateFromProps()
   ⤷ 6. Child render()
   ⤷ 7. Child componentDidMount()
  8. Parent componentDidMount()

# High Order Components
 A Higher-Order Component (HOC) in React is a function that takes a component and returns a new component with added functionality.

Think of it like a wrapper that enhances or modifies the behavior of the original component without changing its source code. 

# Redux Toolkit
 -Install @reduxjs/toolkit and react-redux
 -Build our Store
 -Connect our store to our app
 -dispatch(action)
 -Selector