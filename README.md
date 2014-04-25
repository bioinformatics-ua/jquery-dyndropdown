        <table>
            <tr>
                <th>Property</th>
                <th>Values Possible</th>
                <th>Decription</th>
            </tr>
            <tr>
                <td>label</td>
                <td>String, default: "Action"</td>
                <td>Label that will appear on the button (or on the menu top in case we are using the plugin without button dropdown.</td>
            </tr>
            <tr>
                <td>dropup</td>
                <td>boolean, default: false</td>
                <td>Indicates if the dropdown should dropup.</td>
            </tr>
            <tr>
                <td>single_choice</td>
                <td>boolean, default: true</td>
                <td>Indicates if multiple selection should be allowed</td>
            </tr>
            <tr>
                <td>left_centered_dropdown</td>
                <td>boolean, default: false</td>
                <td>Indicates if the dropdown should open to the left, instead of the right.</td>
            </tr>
            <tr>
                <td>size</td>
                <td>String, default: null</td>
                <td>Indicates the width of the button eg. '100px'. Can also be a percentage, eg. '100%'.</td>
            </tr>
            <tr>
                <td>button_dropdown</td>
                <td>boolean, default: true</td>
                <td>Indicates if we have a button dropdown, or instead just the dropdown as a menu.</td>
            </tr>
            <tr>
                <td>alwaysOneOption</td>
                <td>boolean default: false</td>
                <td>Indicates if we should always have one option selected of every kind.</td>
            </tr>            
            <tr>
                <td>onSelectionChanged</td>
                <td>function, default: null</td>
                <td>Callback that is executed when there's a change on the menu selections. Receives as input an object with all the selections. E.g. function(selection){ }</td>
            </tr>

        </table>