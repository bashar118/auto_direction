# auto_direction

AutoDirection(
  text: text,
  child: TextField(
    onChanged: (str){
      setState(() {
        text = str;
      });
    },
  ),
)
```
