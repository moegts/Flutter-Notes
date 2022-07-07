- Create App `flutter create appName`
- Check the Flutter env if there is anything wrong `flutter doctor`
- Run the Flutter App `flutter run`
```js
Widget myWidget() {
  return Row(
    children: <Widget>[
      Expanded(
        flex: 7,
        child: Container(
          color: Colors.green,
        ),
      ),
      Expanded(
        flex: 3,
        child: Container(
          color: Colors.yellow,
        ),
      ),
    ],
  );
}
```
