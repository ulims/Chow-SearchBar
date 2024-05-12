# Chow Design Search Bar

[![Version](https://img.shields.io/pub/v/chow_search_bar.svg)](https://pub.dev/packages/chow_search_bar) [![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-%23FE5196?logo=conventionalcommits&logoColor=white)](https://conventionalcommits.org) 

Chow Design System Search Par

## Usage

```dart
import 'package:chow_search_bar/chow_search_bar.dart';

class ChowApp extends StatelessWidget {
  Widget build(BuildContext context) {
    return Scaffold(
    appBar: AppBar(
    title: const Text('Chow Search Bar'),
    bottom: PreferredSize(
    preferredSize: const Size.fromHeight(50),
    child: ChowSearchField(
    backgroundColor: Theme.of(context).colorScheme.background,
    hinText: 'Search chow...',
    trailingTap: () {},
    active: true,
    onChanged: (value) {
    setState(() {
    text = value;
    });
    },
    onSubmit: (value) {
    setState(() {
    text = value;
    });
    },
    )))
    );
      
  }
}
```




## FAQs

### What is this?

This package gives you access to the Touchableopacity widget. This Package uses the Inkwell to allow interaction and animated to opacity of the widget on touch events.
