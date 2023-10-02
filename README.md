
## Qt-History
##### [Qt]
```
Started in 1994 by Trolltech
In January 2008, Trolltech was acquired by Nokia.
In October 2011, Qt was opened to the community through qt-project.org.
In August 2012, Qt was acquired by Digia.
In September 2014, Qt activities were transferred to The Qt Company.
```

## Qt-Note
##### [Qt]
```
Note 1 : For get help QML type like Rectangle,Select this and press f1
Note 2 : For The placement point of each type of QML is calculated from the location of the parent placement point(x and y ) 
```

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

## QtQuick-qmlproject
##### [Qt]
```
    1- Create Directory
    2- Create File With Extention .qmlproject And Write To File:
        import QmlProject 1.0
        Project {
            mainFile: "one.qml"
        
            QmlFiles {
                directory: "."
            }
        }
    3- Create File With Extention .qml And Write To File:
        import QtQuick 2.0
        
        Item {
            width: 400; height: 200
        
            Rectangle {
            x: 100; y: 50
            height: 100
            width: height * 2
            color: "Lightblue"
            }
        }
    4-Open Qt Creator And Open .qmlproject file And Run



    

```
