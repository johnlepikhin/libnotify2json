# Naive pcre-based parser of libnotify messages from dbus-monitor output

Usage:

 dbus-monitor 'interface=org.freedesktop.Notifications' 'type=method_return' | libnotify2json | ... [your JSON processor]
