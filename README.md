# Change-The-Color-Of-StatusBar-For-Specific-ViewController
This Code Will Change the Statusbar Color According to your need .



Source Link :- https://www.ioscreator.com/tutorials/change-color-status-bar-ios-tutorial


### Put This Code in VIewController 

* For White StatusBar Color

```swift

override var preferredStatusBarStyle: UIStatusBarStyle {
    return .lightContent
}

```

* For Black StatusBar Color (It is Defualt )

```swift

override var preferredStatusBarStyle: UIStatusBarStyle {
    return .defualt
}

```

* For NavigationController StatusBar Color Change

```swift

override func viewDidAppear(_ animated: Bool) {
    navigationController?.navigationBar.barStyle = .black
}

```
