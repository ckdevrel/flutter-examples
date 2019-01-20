
<a href='https://ko-fi.com/U6U0GSTS' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://az743702.vo.msecnd.net/cdn/kofi3.png?v=0' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>


# Getting Started

- [Getting Started](#getting-started)
  - [Widgets](#widgets)
  - [Container](#container)
  - [Text](#text)
  - [Icon](#icon)
  - [Button](#button)
  	- [Flat Button](#flat-button)
  	- [Raised Button](#raised-button)
  	- [Icon Button](#icon-button)
  - [Row](#row)
    - [MainAxisAlignment](#mainaxisalignment)
    - [CrossAxisAlignment](#crossaxisalignment)
  - [Column](#column)
    - [MainAxisAlignment](#mainaxisalignment)
    - [CrossAxisAlignment](#crossaxisalignment)
  - [TextField](#TextField)
    - [Under Line Style ](#under-line-style )   
    - [Outer Line Style ](#outer-line-style )  

  - [Utilities](#utilities)

  - [Row](#row)
  - [Column](#column)
  

- [Utilities](#utilities)

## Widgets

## Container
<a href="https://imgur.com/pGA1yrB"><img src="https://imgur.com/pGA1yrB.png" title="source: imgur.com"></a>

```dart
Container(
  padding: const EdgeInsets.all(0.0),
  alignment: Alignment.center,
  color: Colors.cyanAccent,
  width: 80.0,
  height: 80.0,
),
```

## Text
<a href="https://imgur.com/yZPgBPy"><img src="https://imgur.com/yZPgBPy.png" title="source: imgur.com"></a>

```dart
new Text(
  "Flutter is Awesome",
  style: new TextStyle(
      fontSize: 18.0,
      color: Colors.greenAccent,
      fontWeight: FontWeight.w500,
      fontFamily: "Roboto"),
),
```

## Icon
<a href="https://imgur.com/QGPuoR5"><img src="https://imgur.com/QGPuoR5.png" title="source: imgur.com"></a>

```dart
new Icon(Icons.flight_takeoff, color: Colors.blueAccent, size: 96.0),
```

## Button

### Flat Button

<a href="https://imgur.com/21VBE83"><img src="https://imgur.com/21VBE83.png" title="source: imgur.com"></a>

```dart
FlatButton(
  onPressed: () {
    debugPrint('I am Awesome');
  },
  textColor: Colors.white,
  color: Colors.blueAccent,
  disabledColor: Colors.grey,
  disabledTextColor: Colors.white,
  highlightColor: Colors.orangeAccent,
  child: Text('Flat Button'),
),
```    

### Raised Button


<a href="https://imgur.com/AtcNtCK"><img src="https://imgur.com/AtcNtCK.png" title="source: imgur.com"></a>

```dart
RaisedButton(
  onPressed: () {
    debugPrint('I am Awesome');
  },
  textColor: Colors.white,
  color: Colors.blueAccent,
  disabledColor: Colors.grey,
  disabledTextColor: Colors.white,
  highlightColor: Colors.orangeAccent,
  elevation: 4.0,
  child: Text('Raised Button'),
),
```  

### Icon Button

<a href="https://imgur.com/Sj0JzHc"><img src="https://imgur.com/Sj0JzHc.png" title="source: imgur.com"></a>

```dart
IconButton(
  onPressed: () {
    debugPrint("Starred Me!");
  },
  color: Colors.orangeAccent,
  icon: Icon(Icons.star),
  disabledColor: Colors.grey,
  highlightColor: Colors.black38,
),
```       
## Row

### MainAxisAlignment

> **Note:** The below example is with **CrossAxisAlignment.center**

|.center|.start|.end|
|:--:|:--:|:--:|
|<a href="https://imgur.com/XR3dmJc"><img src="https://imgur.com/XR3dmJc.png" title="source: imgur.com"></a> |<a href="https://imgur.com/bPfPpsp"><img src="https://imgur.com/bPfPpsp.png" title="source: imgur.com"></a>|<a href="https://imgur.com/edkXXp7"><img src="https://imgur.com/edkXXp7.png" title="source: imgur.com"></a>|


|.spaceEvenly|.spaceAround|.spaceBetween|
|:--:|:--:|:--:|
|<a href="https://imgur.com/iX1G0F6"><img src="https://imgur.com/iX1G0F6.png" title="source: imgur.com"></a> |<a href="https://imgur.com/FJJdzF8"><img src="https://imgur.com/FJJdzF8.png" title="source: imgur.com"></a>|<a href="https://imgur.com/LzPcqi1"><img src="https://imgur.com/LzPcqi1.png" title="source: imgur.com"></a>|

### CrossAxisAlignment

|.center|.start|.end|.stretch|
|:--:|:--:|:--:|:--:|
|<a href="https://imgur.com/XR3dmJc"><img src="https://imgur.com/XR3dmJc.png" title="source: imgur.com"></a> |<a href="https://imgur.com/BP6U9HI"><img src="https://imgur.com/BP6U9HI.png" title="source: imgur.com"></a>|<a href="https://imgur.com/CR2ZDSo"><img src="https://imgur.com/CR2ZDSo.png" title="source: imgur.com"></a>|<a href="https://imgur.com/hS1Pu4G"><img src="https://imgur.com/hS1Pu4G.png" title="source: imgur.com"></a>|

```dart
Row(
  mainAxisAlignment: MainAxisAlignment.center,
  mainAxisSize: MainAxisSize.max,
  crossAxisAlignment: CrossAxisAlignment.center,
  children: <Widget>[
  Container(
    padding: const EdgeInsets.all(0.0),
    alignment: Alignment.center,
    color: Colors.cyanAccent,
    width: 80.0,
    height: 80.0,
  ),
  Container(
    padding: const EdgeInsets.all(0.0),
    alignment: Alignment.center,
    color: Colors.blueAccent,
    width: 80.0,
    height: 80.0,
  ),
  Container(
    padding: const EdgeInsets.all(0.0),
    alignment: Alignment.center,
    color: Colors.orangeAccent,
    width: 80.0,
    height: 80.0,
  ),
  ],
),
 ```     

## Column

### MainAxisAlignment

> **Note:** The below example is with **CrossAxisAlignment.center**

|.center|.start|.end|.spaceEvenly|.spaceAround|.spaceBetween|
|:--:|:--:|:--:|:--:|:--:|:--:|
|<a href="https://imgur.com/AT1WBOy"><img src="https://imgur.com/AT1WBOy.png" title="source: imgur.com"></a> |<a href="https://imgur.com/Df3PZ0E"><img src="https://imgur.com/Df3PZ0E.png" title="source: imgur.com"></a>|<a href="https://imgur.com/05M0SFS"><img src="https://imgur.com/05M0SFS.png" title="source: imgur.com"></a>|<a href="https://imgur.com/5FxzrUt"><img src="https://imgur.com/5FxzrUt.png" title="source: imgur.com"></a> |<a href="https://imgur.com/wB5u6vW"><img src="https://imgur.com/wB5u6vW.png" title="source: imgur.com"></a>|<a href="https://imgur.com/XB6aNuj"><img src="https://imgur.com/XB6aNuj.png" title="source: imgur.com"></a>|

### CrossAxisAlignment

|.center|.start|.end|.stretch|
|:--:|:--:|:--:|:--:|
|<a href="https://imgur.com/AT1WBOy"><img src="https://imgur.com/AT1WBOy.png" title="source: imgur.com"></a> |<a href="https://imgur.com/HQt271d"><img src="https://i.imgur.com/HQt271d.png" title="source: imgur.com" /></a>|<a href="https://imgur.com/MQP5TwQ"><img src="https://i.imgur.com/MQP5TwQ.png" title="source: imgur.com" /></a>|<a href="https://imgur.com/9Fg9018"><img src="https://i.imgur.com/9Fg9018.png" title="source: imgur.com" /></a>|


```dart
Column(
  mainAxisAlignment: MainAxisAlignment.center,
  mainAxisSize: MainAxisSize.max,
  crossAxisAlignment: CrossAxisAlignment.center,
  children: <Widget>[
    Container(
      padding: const EdgeInsets.all(0.0),
      alignment: Alignment.center,
      color: Colors.cyanAccent,
      width: 80.0,
      height: 80.0,
    ),
    Container(
      padding: const EdgeInsets.all(0.0),
      alignment: Alignment.center,
      color: Colors.blueAccent,
      width: 80.0,
      height: 80.0,
    ),
    Container(
      padding: const EdgeInsets.all(0.0),
      alignment: Alignment.center,
      color: Colors.orangeAccent,
      width: 80.0,
      height: 80.0,
    ),
  ],
),
 ```     

## TextField
(Text box or Edit Text)

### Under Line Style 

|     Simple     |
|----------------|
|<a href="https://imgur.com/UumXHqu"><img src="https://imgur.com/UumXHqu.png" title="source: imgur.com"></a>|

|     Simple     |            Icon               |
|----------------|-------------------------------|
|<a href="https://imgur.com/UumXHqu"><img src="https://imgur.com/UumXHqu.png" title="source: imgur.com"></a>|<a href="https://imgur.com/NZAz3op"><img src="https://imgur.com/NZAz3op.png" title="source: imgur.com"></a>
||`InputDecoration(icon: Icon(Icons.account_circle, color: Colors.blue))`|

|     Prefix     |            Suffix             |
|----------------|-------------------------------|
|<a href="https://imgur.com/wyz5J33"><img src="https://imgur.com/wyz5J33.png" title="source: imgur.com"></a>|<a href="https://imgur.com/yBSuZ5S"><img src="https://imgur.com/yBSuZ5S.png" title="source: imgur.com"></a>|
|`InputDecoration(prefixIcon: Icon(Icons.account_circle, color: Colors.blue))`|`InputDecoration(suffixIcon: Icon(Icons.account_circle, color: Colors.blue))`|

```dart
TextField(
  decoration: InputDecoration(
  hintText: "Enter your name!",
  hintStyle: TextStyle(fontWeight: FontWeight.w300, color: Colors.blue),
  enabledBorder: new UnderlineInputBorder(
      borderSide: new BorderSide(color: Colors.blue)),
  focusedBorder: UnderlineInputBorder(
    borderSide: BorderSide(color: Colors.orange),
  ),
  ),
)
```     

### Outer Line Style 

<a href="https://imgur.com/Lkq5WG2"><img src="https://imgur.com/Lkq5WG2.png" title="source: imgur.com"></a>

```dart
TextField(
  decoration: InputDecoration(
  hintText: "Enter your name!",
  hintStyle: TextStyle(fontWeight: FontWeight.w300, color: Colors.blue),
  enabledBorder: new OutlineInputBorder(
      borderSide: new BorderSide(color: Colors.blue)),
  focusedBorder: OutlineInputBorder(
    borderSide: BorderSide(color: Colors.orange),
  ),
  ),
)
```

> **Note:** Icon, Prefix Icon and Suffix Icon are similar to Underline TextField


## Utilities

Creates Color Utils
```dart
class AppColors {
  static const Color colorPrimary = Color.fromARGB(255, 51, 51, 51);
  static const Color colorPrimaryDark = Color.fromARGB(255, 41, 41, 41);
  static const Color colorAccent = Color.fromARGB(255, 30, 198, 89);
  static const Color yellow = Color.fromARGB(255, 252, 163, 38);
  static const Color orange = Color.fromARGB(255, 252, 109, 38);
  static const Color grey_unselected = Color.fromARGB(255, 96, 96, 96);
  static const Color white_card = Color.fromARGB(255, 250, 250, 250);
  static const Color chrome_grey = Color.fromARGB(255, 240, 240, 240);
  static const Color white = Color.fromARGB(255, 255, 255, 255);
  static const Color white_secondary = Color.fromARGB(255, 220, 220, 220);
  static const Color white_un_selected = Color.fromARGB(255, 180, 180, 180);
  static const Color indigo = Color.fromARGB(255, 51, 105, 231);
  static const Color primary_text = Color.fromARGB(255, 51, 51, 51);
  static const Color secondary_text = Color.fromARGB(255, 114, 114, 114);
  static const Color grey = Color.fromARGB(255, 188, 187, 187);
}
```
