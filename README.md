
# Breakpoint

![version](https://img.shields.io/github/manifest-json/v/Natjo/breakpoint)  

  
Trig when viewport width is bigger or smaller than breakpoint

## Parameters
| Parameter | Type | Default | Description |
| ------ | ------ | ------ | ------ |
| value | number | - | value of breakpoint in px |

## Events
| Name | Arguments | Description |
| ------ | ------ | ------ |
| breakpoint.under() | - | - |
| breakpoint.above() | - | - |


## Usage
```javascript
import Breakpoint from '../../modules/breakpoint/breakpoint.js';

const breakpoint =  new Breakpoint(500);

breakpoint.under = () => {
	console.log('under');
}
breakpoint.above = () => {
	console.log('above');
}
```

## Demo





[See codepen demo](https://codepen.io/natjo/pen/qBardRr?editors=0011)
