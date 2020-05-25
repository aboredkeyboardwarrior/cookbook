import React from "react"

function FormComponent(props) {
    return (
        <main>
            <form>
                <input 
                    name= # textbox key
                    value= # {props.data.<textbox key>} 
                    onChange={props.handleChange} 
                    placeholder= # placeholder
                />
                
                <br />
                
                <label>
                    <input                         
                        type="checkbox"
                        name= # checkbox key
                        onChange={props.handleChange}
                        checked= # {props.data.<checkbox key>}
                    /> # insert label for checkbox
                </label>
                
                
                <button>Submit</button>
            </form>
            <hr />
            
            <h2>Entered information:</h2>
            <p>TextBox: {props.data.<textbox key>}</p>
            <p>Vegan: {props.data.<checkbox key> ? "Yes" : "No"}</p>

            
        </main>
    )
}

export default FormComponent
