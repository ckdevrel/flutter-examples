# Flutter Snippets
A curated collection of most frequently used flutter snippets


- [Material Design](#material)
- [Context](#context)
- [Fragment](#fragment)
- [Activity](#activity)
- [ViewGroup](#viewgroup)
- [TextView](#textview)
- [String](#string)
- [Other](#other)

## Material



```dart
/**
 * Extension method to provide simpler access to {@link View#getResources()#getString(int)}.
 */
fun View.getString(stringResId: Int): String = resources.getString(stringResId)
```

## Utils

### Creating Color Utils

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

  static const Color github_blue = Color.fromARGB(255, 64, 120, 192);
  static const Color github_black = Color.fromARGB(255, 37, 41, 46);
  static const Color github_icons_grey = Color.fromARGB(255, 200, 201, 203);

  static const Color indigo = Color.fromARGB(255, 51, 105, 231);

  static const Color primary_text = Color.fromARGB(255, 51, 51, 51);
  static const Color secondary_text = Color.fromARGB(255, 114, 114, 114);

  static const Color so_orange = Color.fromARGB(255, 244, 128, 36);
  static const Color grey = Color.fromARGB(255, 188, 187, 187);

}
```dart

