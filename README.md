
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
  - [Column](#column)
    - [MainAxisAlignment](#mainaxisalignment)
  - [TextField](#TextField)
    - [Under line style ](#under-line-style )  
    - [Under line Icon style ](#under-line-icon-style )  
    - [Under line Prefix Icon style ](#under-line-prefix-icon-style )  
    - [Under line Suffix Icon style ](#under-line-suffix-icon-style )  

  - [Utilities](#utilities)

  - [Row](#row)
  - [Column](#column)
  

- [Utilities](#utilities)

## Widgets

## Container
![containers.png]({{site.baseurl}}/media/containers.png)

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
![text.png]({{site.baseurl}}/media/text.png)

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
![icon.png]({{site.baseurl}}/media/icon.png)

```dart
new Icon(Icons.flight_takeoff, color: Colors.blueAccent, size: 96.0),
```

## Button

## Flat Button


![flat_ button.png]({{site.baseurl}}/media/flat_ button.png)

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

## Raised Button


![raisedbutton.png]({{site.baseurl}}/media/raisedbutton.png)

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

## Icon Button

![icon_button.png]({{site.baseurl}}/media/icon_button.png)

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

|.center|.start|.end|
|:--:|:--:|:--:|
|![row_center.png]({{site.baseurl}}/media/row_center.png) |![row_start.png]({{site.baseurl}}/media/row_start.png)|![row_end.png]({{site.baseurl}}/media/row_end.png)|


|.spaceEvenly|.spaceAround|.spaceBetween|
|:--:|:--:|:--:|
|![row_equally.png]({{site.baseurl}}/media/row_equally.png) |![row_around.png]({{site.baseurl}}/media/row_around.png) |![row_between.png]({{site.baseurl}}/media/row_between.png)|


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

|.center|.start|.end|.spaceEvenly|.spaceAround|.spaceBetween|
|:--:|:--:|:--:|:--:|:--:|:--:|
|![col_center.png]({{site.baseurl}}/media/col_center.png) |![col_start.png]({{site.baseurl}}/media/col_start.png)|![col_end.png]({{site.baseurl}}/media/col_end.png)|![col_equally.png]({{site.baseurl}}/media/col_equally.png) |![col_around.png]({{site.baseurl}}/media/col_around.png) |![col_between.png]({{site.baseurl}}/media/col_between.png)|


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

### Under line style 

![UnderLineTextField.png]({{site.baseurl}}/UnderLineTextField.png)


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

### Under line Icon style

![UnderLineTextFieldIcon.png]({{site.baseurl}}/UnderLineTextFieldIcon.png)


```dart
InputDecoration(
  icon: Icon(Icons.account_circle, color: Colors.blue))
```

### Under line Prefix Icon style

![UnderLineTextFieldPrefixIcon.png]({{site.baseurl}}/UnderLineTextFieldPrefixIcon.png)

```dart
InputDecoration(
  prefixIcon: Icon(Icons.account_circle, color: Colors.blue))
```

### Under line Suffix Icon style

![UnderLineTextFieldSuffixIcon.png]({{site.baseurl}}/UnderLineTextFieldSuffixIcon.png)


```dart
InputDecoration(
  suffixIcon: Icon(Icons.account_circle, color: Colors.blue))
```
             
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
