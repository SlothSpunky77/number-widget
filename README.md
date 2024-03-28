# number-widget
### This is a simple number widget that you can use to change the number value using '+' and '-'. 
## Usage:
```
import 'package:number_widget.dart';
```
...
```
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
```
