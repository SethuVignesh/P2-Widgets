# P2-Widgets
initial commit
To create a widget requires four steps:

Design the widget layout. At the very least, you will need one layout file describing your widget layout. However, you can also provide additional layout files for
The widget before it receives any data.
The widget on a lockscreen (Android 4.0 and above).
The widget on a lockscreen before it receives any data (Android 4.0 and above).
Extend AppWidgetProvider. This class provides methods that are called during a widget lifecycle.
Provide the AppWidgetProviderInfo metadata. Essential information about the widget, such as minimum width and height, update frequency, and more.
Add the widget to your application manifest.
