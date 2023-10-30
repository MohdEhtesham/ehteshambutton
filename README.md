Button Components is helpful to reuse the button in the hole projects this
package will help to use custom button

## Features

This is helpful to make a custom button that provide a unique code .

## Getting started
import 'package:ehteshambutton/ehteshambutton.dart';

CustomButton(
text: "Click Me",
onPressed: () {
// Your button click action here
},
color: Colors.green, // Optional: customize the button color
width: 200.0,         // Optional: customize the button width
height: 60.0,         // Optional: customize the button height
borderRadius: 20.0,   // Optional: customize the border radius
)


## Usage

import 'package:flutter/material.dart';
import 'package:ehteshambutton/ehteshambutton.dart';

void main() {
runApp(MyApp());
}

class MyApp extends StatelessWidget {
@override
Widget build(BuildContext context) {
return MaterialApp(
home: Scaffold(
appBar: AppBar(
title: Text('Custom Button Example'),
),
body: Center(
child: CustomButton(
text: "Successfully",
onPressed: () {
print("Hello");
},
color: Colors.green, // Optional: customize the button color
width: 200.0, // Optional: customize the button width
height: 60.0, // Optional: customize the button height
borderRadius: 20.0, // Optional: customize the border radius
),
),
),
);
}
}




## Additional information

This package make a good way to reuse as a button . 
