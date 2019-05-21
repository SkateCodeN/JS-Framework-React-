# JS-Framework-React-
Learning the react framework 
Here to describe the gist so far of this programming framework lesson

class MyComponent extends React.Component {
  constructor(props) 
{
    super(props);
    this.state = {
      itemCount: 0
    };
    
// change code below this line

    // change code above this line
  }
  

// Tis is bound up top. So when this method is called we increment the property
this.state in the My Component Class

addItem() {
 
   
this.setState({
      
itemCount: this.state.itemCount + 1
    
});
 
 }
  
render() 
	{
    
return (
      
	<div>
        { /* change code below this line */ }
 
		//HTML Class with {JSX} code that calls the methos addItem      
 	 <button onClick= {this.addItem}> Click Me</button>
       
 		{ /* change code above this line */ }
 
       		// This calls the state of itemCount to be updated
	 <h1>Current Item Count: {this.state.itemCount}</h1>
      
	</div>
    );
  
}

};
