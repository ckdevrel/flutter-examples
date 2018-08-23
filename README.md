
<a href='https://ko-fi.com/U6U0GSTS' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://az743702.vo.msecnd.net/cdn/kofi3.png?v=0' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>


# Getting Started

- [Widgets](#widgets)
  - [Container](#container)
  - [Text](#text)
  - [Icon](#icon)
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

## Row

### MainAxisAlignment

|.center|.start|.end|
|:--:|:--:|:--:|
|![row_center.png]({{site.baseurl}}/media/row_center.png) |![row_start.png]({{site.baseurl}}/media/row_start.png)|![row_end.png]({{site.baseurl}}/media/row_end.png)|


|.spaceEvenly|.spaceAround|.spaceBetween|
|:--:|:--:|:--:|
|![row_equally.png]({{site.baseurl}}/media/row_equally.png) |![row_between.png]({{site.baseurl}}/media/row_between.png) |![row_around.png]({{site.baseurl}}/media/row_around.png)|


```dart
   Container(
        padding: const EdgeInsets.all(20.0),
        alignment: Alignment.center,
        color: Colors.grey.shade300,
        height: 140.0,
        child: new Row(
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
      ),
 ```     

## Column

|.center|.start|.end|.spaceEvenly|.spaceAround|.spaceBetween|
|:--:|:--:|:--:|:--:|:--:|:--:|
|![col_center.png]({{site.baseurl}}/media/col_center.png) |![col_start.png]({{site.baseurl}}/media/col_start.png)|![col_end.png]({{site.baseurl}}/media/col_end.png)|![col_equally.png]({{site.baseurl}}/media/col_equally.png) |![col_between.png]({{site.baseurl}}/media/col_between.png) |![col_around.png]({{site.baseurl}}/media/col_around.png)|



```dart
Container(
        alignment: Alignment.center,
        color: Colors.grey.shade300,
        height: 300.0,
        width: 120.0,
        child: new Column(
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
      ),
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
