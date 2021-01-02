# toggling-button-in-Reactjs-by-state

``` JavaScript 
export default class App extends React.Component{

  state = {

    show: false

  }

  Add = ()=>{

    this.setState({

      show: !this.state.show

    })

  }

  render(){

    return(

      <>

         { this.state.show ? <h1> hi </h1>:null}

        <button onClick={this.Add}> set</button>

      </>

    )

  }

}
```
### toggling-button-in-Reactjs-by-Hooks
``` JavaScript
import React ,{useState} from "react";
import "./styles.css";
export default function All(){

  var [set , setplay] = useState(false);

   Hi = ()=> {
   setplay(!set)
}

return (
  <div>

    { set ? <h1>  kdjhd </h1>: null}

    <button onClick={Hi}> ok </button>

  </div>

  )

}
```
