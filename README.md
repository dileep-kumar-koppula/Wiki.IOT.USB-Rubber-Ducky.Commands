# DigiKeyboard Key Code Reference
## Usage
   + Using Key
     ```cpp
     DigiKeyboard.sendKeyStroke(KEY_G);
     ```
   + Code
     ```cpp
     DigiKeyboard.sendKeyStroke(10);
     ```
   + Combinations
     ```cpp
     DigiKeyboard.sendKeyStroke(KEY_2, MOD_SHIFT_LEFT);
     ```
-
## Alphabets
   | Key | Code | Output |
   |:---:|:----:|:------:|
   | KEY_A | 4 | a |
   | KEY_B | 5 | b |
   | KEY_C | 6 | c |
   | KEY_D | 7 | d |
   | KEY_E | 8 | e |
   | KEY_F | 9 | f |
   | KEY_G | 10 | g |
   | KEY_H | 11 | h |
   | KEY_I | 12 | i |
   | KEY_J | 13 | j |
   | KEY_K | 14 | k |
   | KEY_L | 15 | l |
   | KEY_M | 16 | m |
   | KEY_N | 17 | n |
   | KEY_O | 18 | o |
   | KEY_P | 19 | p |
   | KEY_Q | 20 | q |
   | KEY_R | 21 | r |
   | KEY_S | 22 | s |
   | KEY_T | 23 | t |
   | KEY_U | 24 | u |
   | KEY_V | 25 | v |
   | KEY_W | 26 | w |
   | KEY_X | 27 | x |
   | KEY_Y | 28 | y |
   | KEY_Z | 29 | z |

## Numbers
   | Key | Code | Output |
   |:---:|:----:|:------:|
   | KEY_1 | 30 | 1 |
   | KEY_2 | 31 | 2 |
   | KEY_3 | 32 | 3 |
   | KEY_4 | 33 | 4 |
   | KEY_5 | 34 | 5 |
   | KEY_6 | 35 | 6 |
   | KEY_7 | 36 | 7 |
   | KEY_8 | 37 | 8 |
   | KEY_9 | 38 | 9 |
   | KEY_0 | 39 | 0 |

## Keys
   | Key | Code | Description |
   |:---:|:----:|:-----------:|
   | KEY_ENTER | 40 | Enter key |
   | KEY_ESCAPE | 41 | Escape key |
   | KEY_BACKSPACE | 42 | Backspace key |
   | KEY_TAB | 43 | Tab key |
   | KEY_SPACE | 44 | Space Key |

## Symbols
   | Key | Code | Output |
   |:---:|:----:|:------:|
   | KEY_MINUS | 45 | - |
   | KEY_EQUAL | 46 | = |
   | KEY_LEFT_BRACE | 47 | [ |
   | KEY_RIGHT_BRACE | 48 | ] |
   | KEY_BACKSLASH | 49 | \ |
   | KEY_SEMICOLON | 51 | ; |
   | KEY_APOSTROPHE | 52 | - |
   | KEY_GRAVE | 53 | Grave |
   | KEY_COMMA | 54 | , |
   | KEY_PERIOD | 55 | . |
   | KEY_SLASH | 56 | / |
   | KEY_CAPS_LOCK | 57 | Caps Lock |

## Function Keys
   | Key | Code | Description |
   |:---------:|:----:|:----------:|
   | KEY_F1 | 58 | F1 key |
   | KEY_F2 | 59 | F2 key |
   | KEY_F3 | 60 | F3 key |
   | KEY_F4 | 61 | F4 key |
   | KEY_F5 | 62 | F5 key |
   | KEY_F6 | 63 | F6 key |
   | KEY_F7 | 64 | F7 key |
   | KEY_F8 | 65 | F8 key |
   | KEY_F9 | 66 | F9 key |
   | KEY_F10 | 67 | F10 key |
   | KEY_F11 | 68 | F11 key |
   | KEY_F12 | 69 | F12 key |

## Other Keys
   | Key | Code | Description |
   |:-----------------:|:----:|:-----------------:|
   | KEY_PRINTSCREEN    | 70   | Print Screen key  |
   | KEY_SCROLL_LOCK     | 71   | Scroll Lock key   |
   | KEY_PAUSE           | 72   | Pause key         |
   | KEY_INSERT          | 73   | Insert key        |
   | KEY_HOME            | 74   | Home key          |
   | KEY_PAGE_UP         | 75   | Page Up key       |
   | KEY_DELETE          | 76   | Delete key        |
   | KEY_END             | 77   | End key           |

## Arrows
   | Key | Code | Description |
   |:---:|:----:|:-----------:|
   | KEY_PAGE_DOWN | 78 | Page Down |
   | KEY_ARROW_RIGHT | 79 | Right Arrow |
   | KEY_ARROW_LEFT | 80 | Left Arrow |
   | KEY_ARROW_DOWN | 81 | Down Arrow |
   | KEY_ARROW_UP | 82 | Up Arrow |

## Keypad buttons
   | Code | Output |
   |:----:|:------:|
   | 83 | Num lock |
   | 84 | / |
   | 85 | * |
   | 86 | - |
   | 87 | + |
   | 88 | Enter key |
   | 89 | 1 |
   | 90 | 2 |
   | 91 | 3 |
   | 92 | 4 |
   | 93 | 5 |
   | 94 | 6 |
   | 95 | 7 |
   | 96 | 8 |
   | 97 | 9 |
   | 98 | 0 |
   | 99 | . |
   | 100 | < |

## Controls
   | Key | Description |
   |:----------------:|:-------------------------------:|
   | MOD_CONTROL_LEFT | Left Control key |
   | MOD_SHIFT_LEFT | Left Shift key |
   | MOD_ALT_LEFT | Left Alt key |
   | MOD_GUI_LEFT | Left Windows logo key |
   | MOD_CONTROL_RIGHT | Right Control key |
   | MOD_SHIFT_RIGHT | Right Shift key |
   | MOD_ALT_RIGHT | Right Alt key |
   | MOD_GUI_RIGHT | Right Windows logo key |

## Others
   Usage:
   ```cpp
   DigiKeyboard.sendKeyStroke('0');
   ```
   + All Respective series i.e. If "2" as an example, all 2 in ten's place (2, 12, 22, 32,....) will work as same
     | Code | Output |
     |:---:|:-----------:|
     | '0' | ] |
     | '1' | \ |
     | '2' | \ |
     | '3' | ; |
     | '4' | ' |
     | '5' | ` |
     | '6' | , |
     | '7' | . |
     | '8' | / |
     | '9' | Shift |
   
   + Only below code will work with combinations
     ```cpp
     DigiKeyboard.sendKeyStroke('20' , '19');
     ```





