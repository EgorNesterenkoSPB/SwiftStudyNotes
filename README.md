# SwiftStudyNotes :octocat:
# Topics with some information to repeat or remember the theme :heart_eyes_cat:
![Alt-userD503](https://quickbirdstudios.com/blog/wp-content/uploads/2021/01/Coordinator-2.jpg)
- [Swift](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Swift)

  - [MVC](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#MVC)

- [SwiftUI](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#SwiftUI)

  - [LifeCycle](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#LifeCycle)
  - [Lottie live animations](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Lottie_Animations)
  - [Local Notification](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Local_Notification)
  - [Limit characters in TextField](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Limit_characters_in_TextField)
  - [MVVM](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#MVVM)
  - [Add AppDelegate and SceneDelegate](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Add_AppDelegate_and_SceneDelegate)
  - [Create one-time welcome view](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Create_one-time_welcome_view)
# SwiftUI

## AVAudioPlayer
Вставляем файл типом mp3 в проект
![Alt-exampl](https://sun9-71.userapi.com/impg/EPfv_8kovU1-3GxomLMeKcjxyDMK5B7wbGlFLA/o81M6MMEvNI.jpg?size=806x374&quality=96&sign=91285bead631eca2c5bcc2209fc5de4b&type=album)

![Alt-example](https://sun9-20.userapi.com/impg/XaLlrK07NddMx3uP-iOCvKaEmOxJlSMaSOzr3Q/1RmOhrbfBho.jpg?size=608x124&quality=96&sign=14961a88b3b40027e68e9e01ac2c93c2&type=album)

## Lottie_Animations

Ссылка на ресурс: https://lottiefiles.com/getting-started

От туда загружаем JSON 

Устанавливаем библиотеку в проект: https://github.com/airbnb/lottie-ios.git

Dead Code Striping устанавливаем на NO в build target чтобы приложение не крашилось 
![Alt-example](https://sun9-52.userapi.com/impg/xH0-wZuv_Ebjfp7bpim9AFO_vXBifYW31PZ8Fg/QqRd38XNEtI.jpg?size=666x698&quality=96&sign=65965c2887d46816aa56856127d1d2ea&type=album)

ВАЖНО заменить В 19 строке на параметр filename чтобы можно было настраивать под другие анимации которые добавлены и LottieView должно быть в любом Stack


## Local_Notification
![Alt-example](https://sun9-28.userapi.com/impg/ANTFZrvis9LC8Yq9dJLJRqE8H1kbLBk5FxQTBA/V0-72Xkgd0w.jpg?size=664x166&quality=96&sign=6e887dc8c714010eb27d330aaa6a1b19&type=album)

Параметр notifications хранит Notofication objects которые создаются

Нужно пользователя спросить его разрешение на отправку уведомлений:
![Alt-example](https://sun9-79.userapi.com/impg/uurEmjGTosYNap5rBxjFrX3WgZKjNfdsxm0JnA/SjPTUT8O1dM.jpg?size=780x236&quality=96&sign=4b3a598ced7d20cc635f0989f0711411&type=album)

UserNotificationCenter – запрашивает delegate на то как использовать уведомления которые поступают пока приложение находится на переднем плане

Badge – использует значок app icon для уведомления 

Sound – произведение звука при уведомлении

Внутри класса создается функция которая используется для установки контента который будет использоваться в уведомлении:
![Alt-example](https://sun9-37.userapi.com/impg/2WaZlCD_TSQ98YQYQsQvoGv4N2B1RAv1pSY_Bg/7vj-tOUl9Sk.jpg?size=936x468&quality=96&sign=85ca07dabd44809f1cb41ff5d51e27cd&type=album)
 
UnNotificationAttachment – медиа файл связанный с уведомлением, например видео, изображение или аудио контент который должен быть на диске и в правильном формате

Устанавливаем триггер для уведомления чтобы оно появилось, на примере ниже это будет временный интервал в 5 секунд:
![Alt-example](https://sun9-75.userapi.com/impg/E77tA--3mT57Es7np1V16R8FyRkZzSbFyM6p2Q/ySxWtWo-BAs.jpg?size=936x222&quality=96&sign=c663fda3cef5ec1b85bbe64f8521ae09&type=album)

UNTimeIntervalNotificationTrigger – триггерное условие которое заставляет систему доставить уведомление после указанного времени

UNNotificationRequest – запрос на назначение локального уведомления, который включает в себя content и trigger условия

Добавляем запрос:
![Alt-example](https://sun9-13.userapi.com/impg/twUe8jZAaEIjFIGz9mnHGFUXZ149AVN60x39Dw/nDA0lagLkco.jpg?size=936x170&quality=96&sign=ccc15cbd569e6953a75fc897dcd8c844&type=album)

![Alt-example](https://sun9-20.userapi.com/impg/ZQb1m57XmlfxQ3vieT51UI7ALiH3tp_F0rastA/-zVPZXyweP8.jpg?size=936x152&quality=96&sign=94cfbbbd706fe6f3303383d9fa81d5f3&type=album)

![Alt-example](https://sun9-71.userapi.com/impg/FJ_Pkie--gNCSJ0ywy9_ZfI_ize8_hn7Q_8l2Q/CNWvRIui9fQ.jpg?size=936x144&quality=96&sign=20ad72f7acc3f6a9f8af8f1917790554&type=album)

## Limit_characters_in_TextField
AudioToolbox фрэймворк нужен чтобы реагировать когда пользователь ввел больше символов чем установлено

![Alt-example](https://sun9-35.userapi.com/impg/__rrevtlkMFKazoJ4H4KRw4Ml1499Fs20x0XvQ/8sgbtEE9ZJA.jpg?size=346x106&quality=96&sign=28b9c44647e301e377c58e4b9ba35732&type=album)

![Alt-example](https://sun9-63.userapi.com/impg/2La2z4M68QHGa5rqgfYKU9g9huo8JeF6bdCv7Q/_4SCarl09Rc.jpg?size=508x202&quality=96&sign=0c164f20ca191f03501d2fd062f8bbe5&type=album)

![Alt-example](https://sun9-54.userapi.com/impg/AxWBcIgJb7Mpu_nMCkzDhCdbzsnomgnXOjVJGA/db7PP8Zc-w8.jpg?size=936x126&quality=96&sign=6777e4f5c6e835b234b5dfcb77c4c323&type=album)

![Alt-example](https://sun9-81.userapi.com/impg/LbaGew7txf_FxsGG_gGNRtbxlTWgSJlOgV4Gcg/HP5xnLFYJn4.jpg?size=936x206&quality=96&sign=5430657fa2896c424dbe09155fbc8f37&type=album)

В параметре userInput делаем didSet чтобы при каждом изменение отслеживалось условие:
![Alt-example](https://sun9-17.userapi.com/impg/WARN0CUFBy0W0vTIPwhTQNFvXT3HpXRHcjQXxg/jgS3B8NZfXg.jpg?size=936x188&quality=96&sign=11a2abd10f640500758a569926c1a7bd&type=album)

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
