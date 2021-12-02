## notify_inapp

show custom in-app notification with any Widgets.

![](https://raw.githubusercontent.com/jiang111/notify_inapp/main/art/art.gif)

## Getting Started

Add this to your package's `pubspec.yaml` file:

```yaml
dependencies:
  notify_inapp: ^0.0.1
```


## Usage

Then you just have to import the package with

```dart
import 'package:notify_inapp/notify_inapp.dart';
```


Show a notifcation

```dart
Notify notify = Notify();
notify.show(
  context,
  child,
);

```

Dismiss a notifcation 

```dart
notify.dismiss();
```


## Show Method Public Params Summary

| Param | Description | Default Value    
| ---- | ---- | ----
|duration | animation duration | 300
|keepDuration| notifcation shown time | 3000
|topOffset| Height from screen top | 40
|dismissDirectly| not show animation when closing notification | false
| disableDrag | disable Drag down | false
         