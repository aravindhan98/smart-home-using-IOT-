# smart-home-using-IOT-
import 'package:flutter/material.dart';

void main() async => runApp(SmartHomePage());
class SmartHomePage extends StatelessWidget {

@override

Widget build(BuildContext context) {

  return new MaterialApp(

    title: "SmartHome",
  );
 }
}
class SmartHomePage extends StatelessWidget {

 @override

Widget build(BuildContext context) {

  return new MaterialApp(

    title: 'SmartHome',

    debugShowCheckedModeBanner: false,

    theme: new ThemeData(

     primarySwatch: Colors.blue,
    )
 }
}


class SmartHomePage extends StatelessWidget {
@override
Widget build(BuildContext context) {
  return new MaterialApp(
    title: 'SmartHome' theme: new ThemeData(
      primarySwatch: Colors.blue,
  ),
    home: Scaffold(
      appBar: AppBar(
      title: Text("Kitchen"),
    )​,
      backgroundColor: Color(0xFF32323e),
      body: Padding(
         padding: const EdgeInsets.symmetric(horizontal: 16.0),
      )),
   );
 }
}
