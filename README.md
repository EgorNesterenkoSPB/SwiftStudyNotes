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

App delegate снабжен `@UIApplicationmain`, который указывает что этот app delegate приложения является отправной точкой приложения

IOS создает экземпляр UIApplication и назначает экземпляр app delegate класса к delegate свойству поэтому можно настраивать что происходит когда приложение запускается

Самая важная функция ```application(_:didFinishLaunchingWithOptions:)```
Используется для:
1.установки Firebase, Parse Server и так далее
2.устанавливать app windows root view controller
3.Изменять внешний вид приложения
4. Отвечать на входящие удаленные или локальные уведомления

App delegate используется также для захвата жизненных происшествий приложения

В SwiftUI App протокол заменяет app delegate

@main атрибут объявляет о структуре указывая что структура содержит верхний уровень входной точки для потока программы

Пример реагирования на фоновое состояние приложения:
![Alt-example](https://sun9-73.userapi.com/impg/mhgmCjfVRh4KcSn-wwhywopy5QiQKmIHUoAz_g/7mad1NpQ2mo.jpg?size=662x428&quality=96&sign=a9b3831f53f8bb63aa65053fbc2cb211&type=album)
 

У ScenePhase есть 3 состояния:
1.	Active – сцена находится на переднем плане и активна
2.	Inactive- сцена на переднем плане но не активна
3.	Background – сцена на текущий момент не отображается 

onChange – метод который запускает замыкание каждый раз когда scenePhase изменяется

Пример установки AppDelegate:

![Alt-example](https://sun9-76.userapi.com/impg/RarWssqC92FGZSluKniyMjoyggCZLZDZzjPg2g/rmxh0qhM7gY.jpg?size=690x500&quality=96&sign=24261dabfbc61b4f5ab9ddae2d78c2a4&type=album)

Функция в scene delegate похожая на didFinishLaunchingWithOptions вызывается когда сцена добавлена в приложение:
`scene(_:willConnectTo:options:)` 


Функция вызывается когда сцена выключилась из приложения
`sceneDidDisconnect(_:)`


Функция вызывается когда пользователь начинает взаимодействовать со сценой например выбирает ее из app switcher
`sceneDidBecomeActive(_:)`

Функция вызывается когда пользователь прекращает взаимодействовать со сценой например переключается на другую сцену
`sceneWillResignActive(_:)`


Функция вызывается когда сцена вступает на передний план например начинается или возобновляется с background
`sceneWillEnterForeground(_:)`


Функция вызывается когда сцена вступает на фон например сведена к минимуму но все еще показывается на фоне
`sceneDidEnterBackground(_:)`

AppDelegate имеет две delegate функции связанные с управлением scene sessions, которые когда сцена создается в приложение отслеживают все информацию касающуюся сцены:

Первая функция которая нужна возвращать конфигурацию объекта когда создается новая сцена
`application(_:configurationForConnecting:options:)`

Вторая функция которая вызывается когда пользователь закрыаает одну или больше сцен в app switcher
`application(_:didDiscardSceneSessions:)`

Application Scene Manifest в info.plist это перечень каждой сцены которая поддерживается приложением


## AddDelegate_SceneDelegate

## Add_AppDelegate_and_SceneDelegate

UIApplicationDelegatorAdapter позволяет ассоциировать делегата приложения

![Alt-example](https://sun9-46.userapi.com/impg/Kf0Tu6qWq4NdjVOd-DsjfA0hBtunWcRyXGmxQA/lAAy0W5PWKQ.jpg?size=936x256&quality=96&sign=fb6e1c29972eac92626b1a0119c21689&type=album)

![Alt-example](https://sun9-25.userapi.com/impg/HPhJkHf2IXsvKJiYtCkgREYGR7TlJ9WGGyPUYg/rM7IsPNLmyE.jpg?size=670x264&quality=96&sign=226b0c6b2258d1f2f587fb2035d09da4&type=album)

Для добавления многих windows – в info.plist в Enable Multiple Windows поставить YES

UISceneDelagate используется для управления жизненными циклами в одном экземпляре пользовательского интерфейса, который определяет методы реагирования на переходные состояния которые влияют на сцена например когда сцена выходит на передний план и становится активной или когда она попадает на фон
Используется для выполнения критической задачи и успокоить приложения когда оно попадает на фон

![Alt-example](https://sun9-21.userapi.com/impg/mOsobT_Gey8O5LW7qr_6loFuvXsdMC4TuVkRjg/vJ-KDt_7ezs.jpg?size=698x426&quality=96&sign=58b0a206e711f49d1c8c1118e1f59b67&type=album)

![Alt-example](https://sun9-65.userapi.com/impg/BBgZ8mVhaf5awu_bRupPrSrQV4HDYT99Z-6W_A/UuVKUECtACA.jpg?size=936x204&quality=96&sign=b192c95cf5421a7728789ee1495f789f&type=album)
 
Добавляем ObservableObject для Environment

![Alt-example](https://sun9-76.userapi.com/impg/SA2RTk9MH5dy3HlmPl08RcZ8t4JWyBcx7G5kgA/Fdn6l62BmEg.jpg?size=936x302&quality=96&sign=0dae8b8e2ec314e664fd8e824a431563&type=album)

![Alt-example](https://sun9-16.userapi.com/impg/KirCIw_K9SaPCHONl7RYL8aSgS3EC_pTB0MqVQ/YccBDBMmIMM.jpg?size=844x282&quality=96&sign=c1cf0f9b51933cb7a5739cd5a1b29625&type=album)

## Create_one-time_welcome_view

## MVVM

# Swift

## MVC
