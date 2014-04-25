

```
$(function(){
            // We initialize the plugin, and update it, always using JSON with the following format
            var json_code = JSON.stringify({
                option_a: {name: 'Option 1'},
                option_b : {
                    name: 'Option 2',
                    values: {
                        response_a: 'a',
                        response_b: 'b'
                    }
                },
                option_c : {
                    name: 'Option 3',
                    values: {
                        response_a: 'c',
                        response_b: 'd',
                        response_c: 'e'
                    }
                }
            });

            var simple = $('#simple_usage').dyndropdown();
            simple.setStructure(json_code);
});
```

Property | Values Possible | Decription
---------|-----------------|-----------
label | String, default: "Action" | Label that will appear on the button (or on the menu top in case we are using the plugin without button dropdown. |
dropup | boolean, default: false | Indicates if the dropdown should dropup. |
| single_choice | boolean, default: true | Indicates if multiple selection should be allowed |
| left_centered_dropdown | boolean, default: false | Indicates if the dropdown should open to the left, instead of the right. |
|size | String, default: null | Indicates the width of the button eg. '100px'. Can also be a percentage, eg. '100%'. |
| button_dropdown | boolean, default: true | Indicates if we have a button dropdown, or instead just the dropdown as a menu. |
| alwaysOneOption | boolean default: false | Indicates if we should always have one option selected of every kind. |
| onSelectionChanged | function, default: null | Callback that is executed when there's a change on the menu selections. Receives as input an object with all the selections. E.g. function(selection){ } |

