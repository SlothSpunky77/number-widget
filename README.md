# number-widget
### This is a simple number widget that you can use to change the number value using '+' and '-'. 
## Usage:
```
import 'package:number_widget.dart';
.
.
.
Row(
  children: [
    Expanded(
      child: Text(
        'Sets: ',
        style:
          TextStyle(color: darkMode.colorScheme.inversePrimary),
    ),
  ),
  NumberStep(
    initialValue: setsCount,
    onValueChanged: (newValue) => setsCount = newValue),
  ],
),
.
.
.
```
##Example:
![image](https://github.com/SlothSpunky77/number-widget/assets/94778190/e83dc652-d0b6-462d-84bd-d99513472007)
