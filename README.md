## QtQuick-QmlScene
##### [Qt]
```
Qt 5 includes qmlscene, a utility that loads and displays QML documents even before the application is complete. This utility also provides the following additional features that are useful while developing QML applications (https://doc.qt.io/qt-5/qtquick-qmlscene.html)

Write Code To Qml File With Name : test.qml

import QtQuick 2.0
Text 
{
    width:300
    height:302
    text: "Hello World"
}
AFTER RUN COMMAND :
    qmlscene test.qml
Note : IF USE LINUX YOU CAN RUN APP WITH : ./test.qml

```
