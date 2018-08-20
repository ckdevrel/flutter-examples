<script type='text/javascript' src='https://ko-fi.com/widgets/widget_2.js'></script><script type='text/javascript'>kofiwidget2.init('Buy us a coffee', '#b446b8', 'U6U0GSTS');kofiwidget2.draw();</script> 


# Getting Started

- [Widgets](#widgets)
  - [Container](#container)
  - [Row](#row)
  - [Column](#column)
  - [Text](#text)
  - [Icon](#icon)

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

## Row
![row.png]({{site.baseurl}}/media/row.png)

```dart
new Row(
        mainAxisAlignment: MainAxisAlignment.start,
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
![column.png]({{site.baseurl}}/media/column.png)

```dart
Column(
        mainAxisAlignment: MainAxisAlignment.start,
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
            color: Colors.orangeAccent,
            width: 80.0,
            height: 80.0,
          ),
        ],
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
