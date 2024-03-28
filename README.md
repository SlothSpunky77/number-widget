# number-widget
### A simple number widget to change the value using '+' and '-'. 
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

### Example:
![image](https://github.com/SlothSpunky77/number-widget/assets/94778190/81ee1072-7afe-449c-ae60-f38f979ce808)
