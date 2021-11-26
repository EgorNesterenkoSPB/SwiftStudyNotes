# SwiftStudyNotes :octocat:
# Topics with some information to repeat or remember the theme :heart_eyes_cat:
![Alt-userD503](https://quickbirdstudios.com/blog/wp-content/uploads/2021/01/Coordinator-2.jpg)
- [Swift](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Swift)

  - [MVC](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#MVC)

- [SwiftUI](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#SwiftUI)

  - [LifeCycle](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#LifeCycle)
  - [MVVM](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#MVVM)
  - [Add AppDelegate and SceneDelegate](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Add_AppDelegate_and_SceneDelegate)
  - [Create one-time welcome view](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Create_one-time_welcome_view)
# SwiftUI

## LifeCycle
Appdelegate – точка входа в приложение, класс управляющим состояним приложения

App delegate снабжен @UIApplicationmain, который указывает что этот app delegate приложения является отправной точкой приложения

IOS создает экземпляр UIApplication и назначает экземпляр app delegate класса к delegate свойству поэтому можно настраивать что происходит когда приложение запускается

Самая важная функция application(_:didFinishLaunchingWithOptions:)
Используется для:
1.установки Firebase, Parse Server и так далее
2.устанавливать app windows root view controller
3.Изменять внешний вид приложения
4. Отвечать на входящие удаленные или локальные уведомления

App delegate используется также для захвата жизненных происшествий приложения

В SwiftUI App протокол заменяет app delegate

@main атрибут объявляет о структуре указывая что структура содержит верхний уровень входной точки для потока программы

Пример реагирования на фоновое состояние приложения
 

У ScenePhase есть 3 состояния:
1.	Active – сцена находится на переднем плане и активна
2.	Inactive- сцена на переднем плане но не активна
3.	Background – сцена на текущий момент не отображается 

onChange – метод который запускает замыкание каждый раз когда scenePhase изменяется

Пример установки AppDelegate:


 


## AddDelegate_SceneDelegate

## Add_AppDelegate_and_SceneDelegate

## Create_one-time_welcome_view

## MVVM

# Swift

## MVC
