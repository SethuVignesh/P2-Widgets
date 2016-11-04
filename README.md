# P2-Widgets
#To create a widget requires four steps:
1)Design the widget layout. At the very least, you will need one layout file describing your widget layout. 
  However, you can also provide additional layout files for
  The widget before it receives any data.
  The widget on a lockscreen (Android 4.0 and above).
  The widget on a lockscreen before it receives any data (Android 4.0 and above).
2)Extend AppWidgetProvider. This class provides methods that are called during a widget lifecycle.
3)Provide the AppWidgetProviderInfo metadata. Essential information about the widget, such as minimum width and height, update frequency, and more.
4)Add the widget to your application manifest.
