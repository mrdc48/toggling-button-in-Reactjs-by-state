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
