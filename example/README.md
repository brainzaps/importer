# Before

```dart
import 'package:flutter/material.dart';
import 'package:flutter/cupertino.dart';
import 'package:flutter/physics.dart';
import 'package:flutter/painting.dart';
import 'package:intl/intl.dart';
import 'package:mdi/mdi.dart';
import 'package:provider/provider.dart';
import 'anotherFile.dart';
import 'package:example_app/anotherFile2.dart';
import 'dart:async';
import 'dart:io';
import 'dart:js';
```

# After

```dart
// Dart imports:
import 'dart:async';
import 'dart:io';
import 'dart:js';

// Flutter imports:
import 'package:flutter/material.dart';
import 'package:flutter/cupertino.dart';
import 'package:flutter/physics.dart';
import 'package:flutter/painting.dart';

// Package imports:
import 'package:intl/intl.dart';
import 'package:mdi/mdi.dart';
import 'package:provider/provider.dart';

// Project imports:
import 'anotherFile.dart';
import 'package:example_app/anotherFile2.dart';
```

# [Example Application](https://github.com/fluttercommunity/import_sorter/tree/master/example/example_app)

Example flutter app using `import_sorter`
