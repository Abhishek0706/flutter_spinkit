# ✨ Flutter Spinkit

[![Build Status - Travis](https://travis-ci.org/jogboms/flutter_spinkit.svg?branch=master)](https://travis-ci.org/jogboms/flutter_spinkit) [![codecov](https://codecov.io/gh/jogboms/flutter_spinkit/branch/master/graph/badge.svg)](https://codecov.io/gh/jogboms/flutter_spinkit) [![pub package](https://img.shields.io/pub/v/flutter_spinkit.svg)](https://pub.dartlang.org/packages/flutter_spinkit)

A collection of loading indicators animated with flutter. Heavily inspired by [@tobiasahlin](https://github.com/tobiasahlin)'s [SpinKit](https://github.com/tobiasahlin/SpinKit).

## 🎖 Installing

```yaml
dependencies:
  flutter_spinkit: "^4.1.0"
```

### ⚡️ Import

```dart
import 'package:flutter_spinkit/flutter_spinkit.dart';
```

## 🎮 How To Use

```dart
const spinkit = SpinKitRotatingCircle(
  color: Colors.white,
  size: 50.0,
);
```

```dart
final spinkit = SpinKitFadingCircle(
  itemBuilder: (BuildContext context, int index) {
    return DecoratedBox(
      decoration: BoxDecoration(
        color: index.isEven ? Colors.red : Colors.green,
      ),
    );
  },
);
```

```dart
final spinkit = SpinKitSquareCircle(
  color: Colors.white,
  size: 50.0,
  controller: AnimationController(vsync: this, duration: const Duration(milliseconds: 1200)),
);
```

For more info, please, refer to the `showcase.dart` in the example.

## 🚀 Showcase

<table>
  <tr>
    <td align="center">
      <img src="https://raw.githubusercontent.com/ybq/AndroidSpinKit/master/art/RotatingPlane.gif" width="100px" height="100px">
      <br />
      RotatingPlain
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/ybq/AndroidSpinKit/master/art/DoubleBounce.gif" width="100px" height="100px">
      <br />
      DoubleBounce
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/ybq/AndroidSpinKit/master/art/Wave.gif" width="100px" height="100px">
      <br />
      Wave
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/ybq/AndroidSpinKit/master/art/WanderingCubes.gif" width="100px" height="100px">
      <br />
      WanderingCubes
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/jogboms/flutter_spinkit/master/screenshots/FadingFour.gif" width="100px" height="100px">
      <br />
      FadingFour
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/jogboms/flutter_spinkit/master/screenshots/FadingCube.gif" width="100px" height="100px">
      <br />
      FadingCube
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://raw.githubusercontent.com/ybq/AndroidSpinKit/master/art/Pulse.gif" width="100px" height="100px">
      <br />
      Pulse
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/ybq/AndroidSpinKit/master/art/ChasingDots.gif" width="100px" height="100px">
      <br />
      ChasingDots
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/ybq/AndroidSpinKit/master/art/ThreeBounce.gif" width="100px" height="100px">
      <br />
      ThreeBounce
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/ybq/AndroidSpinKit/master/art/Circle.gif" width="100px" height="100px">
      <br />
      Circle
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/ybq/AndroidSpinKit/master/art/CubeGrid.gif" width="100px" height="100px">
      <br />
      CubeGrid
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/ybq/AndroidSpinKit/master/art/FadingCircle.gif" width="100px" height="100px">
      <br />
      FadingCircle
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://raw.githubusercontent.com/ybq/AndroidSpinKit/master/art/RotatingCircle.gif" width="100px" height="100px">
      <br />
      RotatingCircle
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/ybq/AndroidSpinKit/master/art/FoldingCube.gif" width="100px" height="100px">
      <br />
      FoldingCube
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/jogboms/flutter_spinkit/master/screenshots/heart.gif" width="100px" height="100px">
      <br />
      PumpingHeart
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/jogboms/flutter_spinkit/master/screenshots/dual-ring.gif" width="100px" height="100px">
      <br />
      DualRing
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/jogboms/flutter_spinkit/master/screenshots/hour-glass.gif" width="100px" height="100px">
      <br />
      HourGlass
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/jogboms/flutter_spinkit/master/screenshots/PouringHourGlass.gif" width="100px" height="100px">
      <br />
      PouringHourGlass
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://raw.githubusercontent.com/jogboms/flutter_spinkit/master/screenshots/grid.gif" width="100px" height="100px">
      <br />
      FadingGrid
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/jogboms/flutter_spinkit/master/screenshots/ring.gif" width="100px" height="100px">
      <br />
      Ring
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/jogboms/flutter_spinkit/master/screenshots/ripple.gif" width="100px" height="100px">
      <br />
      Ripple
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/jogboms/flutter_spinkit/master/screenshots/spinning-circle.gif" width="100px" height="100px">
      <br />
      SpinningCircle
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/abhishek0706/flutter_spinkit/square_circle/screenshots/square_circle.gif" width="100px" height="100px">
      <br />
      SquareCircle
    </td>
  </tr>
</table>

> Some GIF images gotten from [Android Spinkit](https://github.com/ybq/Android-SpinKit).

## 🐛 Bugs/Requests

If you encounter any problems feel free to open an issue. If you feel the library is
missing a feature, please raise a ticket on Github and I'll look into it.
Pull request are also welcome.

### ❗️ Note

For help getting started with Flutter, view our online
[documentation](https://flutter.io/).

For help on editing plugin code, view the [documentation](https://flutter.io/platform-plugins/#edit-code).

## ⭐️ License

MIT License
