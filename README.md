# learning
<mark> JSX </mark>
- JSX is much like HTML with the distinction that you can easily embed dynamic content by writing approriate JavaScript
- React components layout is mostly written by using JSX
- JSX returned by REACT components is compiled into Javascript
- Any Javascript code within the curly braces {} is evaluated.
And the results of this valuation is embedded into the defined place in the HTML produced by the component
- JSX is "XML-like", which means that every tag needs to be closed.
      Exp: HTML: <br> -- line break element
            JSX: <br/> -- line break element
  MULTIPLE COMPONENTS
- A component can be used multiple times
        
- React as "pure Javascript" without using JSX
- Core philosophy of React is composing applications from many specialized reusable components
- strong convention is the <emphasize>root component </emphasize> called <emphasize> App <emphasize>

PASSING DATA TO COMPONENT
- React component use <strong> props <strong/> to communicate with each other
- Props might remind you of HTML attributes but you can pass any JavaScript value through them (objects, arrays, functions)
- Every parent component can pass some information to its child components by giving them props
