# SwiftStudyNotes :octocat:
# Topics with some information to repeat or remember a theme :heart_eyes_cat:
![Alt-userD503](https://quickbirdstudios.com/blog/wp-content/uploads/2019/11/Swift-1.jpg)

- [Machine Learning](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Machine_Learning)
  - [Common information](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Common_Information)
- [Algorithms](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Algorithms)

  - [Search repeating characters in String](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Search_Repeating_Characters_In_String)
  - [Time complexity](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Time_complexity)
  - [Space complexity and Sort method](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Space_complexity)
  - [Data structures](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Data_structures)
    - [Stack](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Stack)
    - [Linked List](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Linked_List)


- [Swift](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Swift)

  - [MVC](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#MVC)
  - [GIT](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#GIT)
  - [GCD](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#GCD)
  - [CoreImage](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#CoreImage)
  - [UIImageWriteToSavedPhotosAlbum](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#UIImageWriteToSavedPhotosAlbum)
  - [Animation](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Animation)
  - [Segue](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Segue)
  - [MapKit](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#MapKit)
  - [WebKit](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#WebKit)
  - [Debugging](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Debugging)
  - [Safari Extension](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Safari_extension)
  - [Keyboard](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Keyboard)
  - [UITextField](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#UITextField)
  - [UNUserNotificationCenter](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#UNUserNotificationCenter)
  - [Protocols](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Protocols)
  - [Delegate Design Patterns](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Delegate_Design_Patterns)
  - [Create custom color / vector image switched w/ dark mode](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Create_custom_color_or_vector_image_switched_with_dark_mode)
  - [API](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#API)
  - [Map](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Map)

- [SwiftUI](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#SwiftUI)

  - [LifeCycle](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#LifeCycle)
  - [AVAudioPlayer](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#AVAudioPlayer)
  - [Lottie live animations](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Lottie_Animations)
  - [Local Notification](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Local_Notification)
  - [Limit characters in TextField](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Limit_characters_in_TextField)
  - [MVVM](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#MVVM)
  - [Add AppDelegate and SceneDelegate](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Add_AppDelegate_and_SceneDelegate)
  - [Create one-time welcome view](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Create_one-time_welcome_view)

## Machine_Learning

## Common_Information

## Algorithms

## Time_complexity

-	это мера времени, необходимого для запуска алгоритма по мере увеличения размера входных данных

1.Constant time algorithm – имеет одинаковое время независимо от размера входящих данных, O(1)

![Alt-example](https://sun9-64.userapi.com/impg/3gW9olrJqTcNjBQv_iuzUIe6_ckjrmMdj7i90Q/qONhVv7Cg68.jpg?size=338x254&quality=96&sign=58a60e7fcdff2a66406b8c1505e47748&type=album)

![Alt-example](https://sun9-85.userapi.com/impg/su38GgMo9PpRKVPwtkmA1ZwXzrlZZVBs6JV9qg/hosQUzVoMKA.jpg?size=362x142&quality=96&sign=4c079b74bc8a7e4b7e7cb1a07e92b18b&type=album)

2.Linear time  - размер данных увеличивается следовательно время выполнения увеличивается, O(n)

![Alt-example](https://sun9-72.userapi.com/impg/ux5eYkn0ghVYthD0opDx1iTv42Yj3-fQJZI5mA/DJhCfiRbEzs.jpg?size=394x304&quality=96&sign=fe590ffe76a35d002a14f8ecb0a7aa5f&type=album) 

![Alt-example](https://sun9-82.userapi.com/impg/vvtyOYA824k5YPTsfAYY5tcEqHIZ-c_kKMLkwA/JnIseopgTl4.jpg?size=408x124&quality=96&sign=43f9a92232f6252bf12eece4e10a5322&type=album)

3.  Quadratic time – временная сложность относится к алгоритму который требует времени пропорционально квадрату входного размера, O(n2)
 
![Alt-example](https://sun9-69.userapi.com/impg/Fi2bnq6Yy9eC0V7Aa3mwwE648BEZlf_CmRDU_g/q8OPxan61N8.jpg?size=424x192&quality=96&sign=89f1b1228798fcea6baba2e6bbc78613&type=album)
 
![Alt-example](https://sun9-12.userapi.com/impg/6U_oC25l2wT33UdnPHxVH4QQpJrd_z3xOtWM2g/BKBgN1PBbEM.jpg?size=376x262&quality=96&sign=52ce68187bb611026189e73d06202c4c&type=album)

4. Logarithmic time – алгоритм который может отбросить половину требуемых сопоставлений, O(log n)

Массив отсортирован:
 
![Alt-example](https://sun9-26.userapi.com/impg/BuZ10dLu8-JlOcL8zDB9W1nbYWO0S9V_YHfwBQ/gyX3cCbS7P4.jpg?size=696x144&quality=96&sign=45ec56fa3683e55fab03ade361d65e2b&type=album) 

![Alt-example](https://sun9-44.userapi.com/impg/W8ISZ2XZ2bJ49NVQ6DcCMs8Q_dBBlSRJct4k8A/In7UJNrEvuc.jpg?size=510x300&quality=96&sign=21949c1201a1d027d61ac3ce1d5b553f&type=album)

![Alt-example](https://sun9-3.userapi.com/impg/H38hYrVDxmjuS51V-aa0X4bGVgxPROy4DpW8wg/QpQi_0HIMGc.jpg?size=376x272&quality=96&sign=bb14cac923368a2ca6ef83759fdd54cf&type=album)
 
5.  Quasilinear time – 0(n log n)

![Alt-example](https://sun9-83.userapi.com/impg/CYEseOwpuZuyzXFCSXcSGQbANWPewb0JUVFeCw/BAgF-09La7M.jpg?size=310x218&quality=96&sign=3a80a8b617fd002e4a7ab264ddef80fe&type=album)

Пример – метод sort

## Space_complexity

Мера ресурсов(память) необходимая для выполнения алгоритмов

![Alt-example](https://sun9-50.userapi.com/impg/csCAxjdrEF9mfPzHTKkB-95tkDP_hMKO-Rq5gg/_HnKt0gy0tA.jpg?size=440x160&quality=96&sign=47ebc8bc42b17223d6d910b846b57dae&type=album)
 
Алгоритм выше создает новый массив с одинаковым размером тогда space complexity – O(n)

![Alt-example](https://sun9-51.userapi.com/impg/aZUhv_3mqdrRZrFGy_szgkUo21Sfuxk3yCzL7g/2bcJayV6zjU.jpg?size=640x500&quality=96&sign=3d27442061503cdffb1aa58272ead207&type=album)
 
Алгоритм выше выделяет память только для отслеживания переменных поэтому space complexity – O(1)

## Data_structures

Поиск конкретного элемента в фиксированном массиве имеет константное время также как и метод append не зависит от размера массива

Если вставлять новый элемент в массив уже с максимальной вместимостью, то копируются все новые элементы в новый и больший контейнер памяти которые автоматически делается в два раза больше прошлого

Вставка и поиск элемента в словаре имеет константное время

## Stack

Push – добавлять элемент на верх стэка
Pop – удалять элемент с верху стэка

Это и есть LIFO(last in first out)

![Alt-example](https://sun9-32.userapi.com/impg/y3HlSBwfvWxC_pQshtol7ykozjrYyIcagefpWQ/j90nO_CdCGU.jpg?size=644x614&quality=96&sign=b5cc83ad16377f83055c005feadec54e&type=album)

![Alt-example](https://sun9-63.userapi.com/impg/gEsWwGgVALrUWNU-0ffEM0PLBtjmnxf2DeDasQ/SHyE0MK9-qY.jpg?size=362x202&quality=96&sign=277458cfa941cab02c8a73c69561500d&type=album)

Также можно добавить в инициализацию storage для уже имеющегося массива:

![Alt-example](https://sun9-35.userapi.com/impg/kcDgR8IGM0euHPNR_CygCkWRSX8f_IPvFodrJw/MCU0nDtCcxQ.jpg?size=630x114&quality=96&sign=6609fed7ca92b8d66bef102273e719a7&type=album)

![Alt-example](https://sun9-3.userapi.com/impg/vDS-KDLGafcviUP1CC7mbhTK8gBne7J_x-zmLw/hOAeEBoFWmw.jpg?size=448x164&quality=96&sign=149bf17b93f319179bce30f02082606b&type=album)

![Alt-example](https://sun9-27.userapi.com/impg/X7G7FBS9GH8SvvVbfyj9-4Psi4X5UW14wMIgzg/_NpjNU0LiMo.jpg?size=144x218&quality=96&sign=bf67c26f93f0dfece2bf01f191be2538&type=album)

## Linked_List

## Search_Repeating_Characters_In_String

`func challenge(input:String) -> Bool {`

`return Set(input).count == input.count}`

Set не может иметь дубликатов


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

## Timer

## MutatingFuncInStruct

## GCD
Operations строится поверх GCD

Все задачи которые GCD управляет находятся в GCD менэджере FIFO очереди

Когда синхронное выполнение задачи, приложение ждет и блокирует текущую выполнение пока не перейдем к следующей задачи

![Alt-example](https://sun9-14.userapi.com/impg/RwvZ8xgIlcD-kA2znEyqkYo-nVc-on7UH6NfAg/JsvLAa3G8Gg.jpg?size=538x254&quality=96&sign=c301fddef7651174e774651bae8ebd82&type=album)
![Alt-example](https://sun9-48.userapi.com/impg/fMvrtb_bgAPF71-vCq-9ArxEt-OJcYJF2bKeLA/FE2Osgkj_Ag.jpg?size=536x248&quality=96&sign=6ca435d2e673b9de69f3e71722e91db2&type=album)
 

Serial and concurrent queues:

![Alt-example](https://sun9-51.userapi.com/impg/0VXvJQP8SnWrsmJAbi4Ufn1T8yGCXBQQHg2Sew/zIB7aVQJ08U.jpg?size=432x340&quality=96&sign=4e0cc3cbc0976144e351e71a7584dfde&type=album)

Serial async queue означает что каждая задача полностью завершается до того как началась следующая задача

Чтобы создать concurrency очередь нужно задать ей приоритет:

Есть 4 фоновых очереди: Quality if service QOS:

1.User interactive – высокий приоритет фоновой очереди, используется когда нужно чтобы фоновый поток поддерживал пользовательский интерфейс в работе, данный приоритет просит выделить всю доступную CPU чтобы выполнить задачу так быстро как возможно

2.User initiated – используется для задач запрошенных пользователем, которые сейчас ждут, чтобы продолжить работу приложения, например при нажатие на кнопку нужно прочитать database

3.  The Utility queue – используется для задач долгих в исполнение при этом пользователь может выполнять другие функции не обращая внимания на данную задачу

4.  The background queue – используется для долгих задач, которые не волнуют пользователя когда они завершатся


Default queue – приоритет между user initiated и utility :

DispatchQueue.global().async {} для default queue

DispatchQueue.global(qos: .userInitiated).async{}

Все методы которые связано с показом на UI нужно оборачивать в DispatchQueue.main().asinc{} если используются код который их затрагивает в background thread 

performSelector(inBackground: или onMainThread:) – свойство которое принимает метод и в зависимости от аргумента запускает данный метод в основном или фоновом потоке

![Alt-example](https://sun9-28.userapi.com/impg/5oMW71vTMg6SB70jGCXvkDZJGR4gUNtkRnA0aA/d4_wCkmKBXI.jpg?size=654x516&quality=96&sign=0655c875a25f2f5b2a12897fdc5d2b75&type=album)

![Alt-example](https://sun9-69.userapi.com/impg/pllabKm1yu4_qayf_LW2jT18XHXSdTvUC6PQoQ/-RPcDNssFps.jpg?size=616x146&quality=96&sign=0d6f716d523464f28820746e624d63b9&type=album)

DispatchGroup – класс используемый для отслеживания выполнения группы задач 

![Alt-example](https://sun9-38.userapi.com/impg/oz6BlQuuLN__BImKR5NbbFuLnbVtKFjJCl3-cQ/WHNWfKnn7cc.jpg?size=598x192&quality=96&sign=687146db7ce8438f1240ef556f99c421&type=album)

Группы используется не только для одиночной очереди
Notify метод уведомляет когда каждая работа завершена

Synchronous method блокирует текущую очередь пока все работы не будут завершены:
Пример с использованием .wait(timeout:) :

![Alt-example](https://sun9-35.userapi.com/impg/8jBivbIK_tuDOc12v5ltcVpSD94d6MLWNsM4bQ/XnZ06A-9eRw.jpg?size=542x178&quality=96&sign=d276134cee4a697e6be3312df277e6c5&type=album)
 
В аргументе устанавливаем сколько времени дается на выполнение задач до того как запуститься код в замыкание в методе wait

Wait нельзя использовать в main queue

![Alt-example](https://sun9-6.userapi.com/impg/_5HdfzXJUwEPBqQdmIjx0xYoInlX0kbYY17xoA/62u9GcjXQvs.jpg?size=590x400&quality=96&sign=d0d783a5eff90b97308535e682885e49&type=album)

Что использовать асинхронный метод внутри другого асинхронного метода – нужно использовать group.enter() и group.leave() которые условно говоря поднимают приоритет выполнения кода и затем его опускает на прежний уровень

![Alt-example](https://sun9-44.userapi.com/impg/kY7XVoICJwYc-jpQ2VOBV-DE1jy7cVnGQjH4yw/E1t3z5Lyi8Q.jpg?size=456x224&quality=96&sign=7e3865125c732568777135b240b52110&type=album) 

Код в замыкание defer будет выполняться после того как закончит выполнение код в замыкании внутри которого находится defer

![Alt-example](https://sun9-44.userapi.com/impg/kY7XVoICJwYc-jpQ2VOBV-DE1jy7cVnGQjH4yw/E1t3z5Lyi8Q.jpg?size=456x224&quality=96&sign=7e3865125c732568777135b240b52110&type=album)

![Alt-example](https://sun9-15.userapi.com/impg/HobQu9r5y2z41f17i9n9hBclmhIayjqG7OwPFg/qfJnk54dzMc.jpg?size=428x220&quality=96&sign=06941a59f637db322f9dadee649a5fe2&type=album)

DispatchSemaphore нужен чтобы ограничить количество параллельных обращений к ресурсу

Let semaphore = DispatchSemaphore(value:4) 
For I in 1…10 {
Queue.async(group:group){
Semaphore.wait() // increment semaphore count
Defer { semaphore . signal() } // decrement semaphore count
Print(“Downloading image \(i)”)
Thread.sleep(forTimeInterval:3 ) // simulate a network wait
Print (“Downloaded image \(i)”)
}
}
Сначала загружаются 4 картинки, потом ожидание 3 секунды, затем еще раз 4 картинки загружаются, ожидание 3 секунды и остальные 2 загружаются картинки


Решение race conditions является в использование serial queue для чтения и записи значения:

![Alt-example](https://sun9-37.userapi.com/impg/ymgJn_Lk33EN_5R1kprMHD6e6_EzAMvY2877Hw/uVB_7SNMIz4.jpg?size=660x274&quality=96&sign=67d239b5365738b90290bfd347c8dcb2&type=album)

Использование барьера при чтение и записи переменной:

![Alt-example](https://sun9-67.userapi.com/impg/WPgketKQdMOMeHcVTlyRwhJ8leKSTaWH0J49HA/KpIRBO5n7vM.jpg?size=644x252&quality=96&sign=ef40c7a679bc4e168b8bd7073daf109c&type=album) 

Барьерная задача не запустится пока все другие задачи не завершатся, как только .barrier задача запуститься очередь сделается serial и только задача барьера может работать сейчас, потом как задача барьера закончится все задачи которые будут выполнятся после барьера начнут работать в параллельной очереди

Deadlock – когда 2 задачи ждут выполнение другой задачи которая никогда не выполнится – для решения ее используются semaphore

Priority inversion – когда высокая уровень очереди делится ресурсами с низким уровнем очереди, которая блокирует объект ,и очередь с высоким уровнем начинает ждать пока очередь с низким уровнем выполнится



Operations
Используется когда нужно чтобы задача выполнялась несколько раз как функцию


Operation имеет машину которая является жизненным циклом:
isReady – когда идет обработка и готов к запуску
isExecuting – начальный метод
isCancelled – когда приложение вызывает данный метод до isFinished
isFinished - метод когда нет isCancelled, напрямую выполняется после isExecuting

![Alt-example](https://sun9-55.userapi.com/impg/MvyLUnSHvMRlq2RrB-KduQ91TXo6VNFxVc92Yg/u5purFETt6A.jpg?size=510x276&quality=96&sign=bf33bf180f6addf3406c19385cc3ba65&type=album)

Данные метода читают только Bool значения, это значит что их можно запрашивать во время выполнения задачи чтобы посмотреть выполняется задача или нет

Когда operation переход имеет isReady, то система знает что она может начать поиск свободного потока, затем когда приемник нашел поток, который выполняет operation, далее operation переходит isExecuting – все выполнение происходит в sync очереди

Создание Operation используя BlockOperation:

![Alt-example](https://sun9-81.userapi.com/impg/Zoq5KZ8y5IC8mak1wGxOlJ9YDK3HsAEYzIcsjw/bcb6E88j7R8.jpg?size=452x94&quality=96&sign=866b56c075e4d58b059ab54317b6b79e&type=album)

BlockOperation управляет текущим выполнением одного или больше замыкания в default global queue
Задачи в BlockOperation выполняются параллельно

В async очереди нужно вручную указывать is… потому что operation не может автоматически определить когда задача завершила выполнение

Отслеживание state в async происходить с помощью KVO уведомлений
Создание subclass AsyncOperation:

![Alt-example](https://sun9-84.userapi.com/impg/7NLTGIN4Ua2x2IwiHbyXgmf4rJ2B29DXJY3FzA/pEaHBVpK3jM.jpg?size=446x182&quality=96&sign=23c64e2b9e72fe598b11da0494b58034&type=album)

Значения которые хранят state
 
![Alt-example](https://sun9-39.userapi.com/impg/wBY2mFqg1BErIiQDhfGXI4PEyyhvuJi5-29XIg/_9g7AgvrF8k.jpg?size=576x206&quality=96&sign=230458b78ce3e4ae2c8371ba9a113c33&type=album)
 
![Alt-example](https://sun9-35.userapi.com/impg/iR42huyAIoFRIiXT64H5LS9Qp8tyyQeYG1U0Ww/Td8E2qdWvZg.jpg?size=616x252&quality=96&sign=e10931bd7b58fa28d02efd04da61b6e1&type=album)
 
![Alt-example](https://sun9-58.userapi.com/impg/FxGR2KRJJKBfgX4apFOKw_UjnALy4P0TBlQwCQ/S0C_s5bLzI0.jpg?size=446x98&quality=96&sign=1c41d83ab18dd4bd0fce7e8cee03c77e&type=album)
 
![Alt-example](https://sun9-61.userapi.com/impg/Lq5DiCsM8epSpnAyEN8sB7DK6PmdqwispwYiGg/dO9kQ2PXrGA.jpg?size=322x102&quality=96&sign=8e17977c114a2eb808587a8573b43f2d&type=album)

Использование subclass AsyncOperation в получение изображения из сети:

![Alt-example](https://sun9-11.userapi.com/impg/_vzKPKIFNiWQATyelP_5kmEV8DYublRSVdXSow/oOUZhQEGPUI.jpg?size=506x174&quality=96&sign=85204b4d9f1e90fc00af3edbc9ec29cf&type=album)

![Alt-example](https://sun9-44.userapi.com/impg/12kQ_FgBOGXLktCXxWwJWyZP6BpZl-hFrJalGg/nZONgOrVQ7g.jpg?size=506x274&quality=96&sign=83831cf5d15684c99c3b622a8dd7917e&type=album)

![Alt-example](https://sun9-25.userapi.com/impg/ZoNg6NRQXS6onA30_s-jD6c2IufwCFyayjj2mg/U2q2hCabp-s.jpg?size=550x156&quality=96&sign=5a6b61ebe5df1dd456a731a1e72dfa5c&type=album) 

![Alt-example](https://sun9-18.userapi.com/impg/47gwb4xbcRoZc_E2ZFQglJzFrRUzJKaRQ2HcQw/noLTNp2UQuM.jpg?size=550x230&quality=96&sign=b2b4243e7f01c23bbc12ff4f3ca3e5ad&type=album)

Взаимоотношения между operations:
.addDependency(op: ) 
.removeDependency(op:) 

![Alt-example](https://sun9-84.userapi.com/impg/ptTKXTpzqJNG00ToSUu-w6F0xnvYlseyRbuI3g/PpvSM00ZBsQ.jpg?size=774x82&quality=96&sign=bbd20e754e880a0d00b8491018ca1a4e&type=album)

![Alt-example](https://sun9-47.userapi.com/impg/CW82vE3IPzpH3JQVJe-NQeQLzDnI9OHHxr4y2w/gO3jpn9PnYo.jpg?size=742x108&quality=96&sign=b48cf5e79302402ecd044cdd10d63891&type=album)

![Alt-example](https://sun9-82.userapi.com/impg/B9CqYPh7NIHRKycwDnhEmKceqr8SJLTbkf40Dg/6qLa3svNu0c.jpg?size=586x128&quality=96&sign=d7cd89b134291d58ddabc4b762092d88&type=album)

![Alt-example](https://sun9-9.userapi.com/impg/hawWQTbRv7or8HrCqxpVfBAad5IcbyVeif6gLg/u-weM5WeLi8.jpg?size=416x60&quality=96&sign=f6140a408e658f03259a898fc4b8c117&type=album)
 
Очередь отслеживает зависимость и tiltShiftop начнется когда download закончится

Чтобы остановить operation– cancel() 
Чтобы остановить все выполнения операций в очереди – cancelAllOperations
В классе AsyncOperation:

![Alt-example](https://sun9-70.userapi.com/impg/peljAYiTNSjvLatry_hO0YR7beqoFXEwP_qXiQ/tcISxtTibdc.jpg?size=294x204&quality=96&sign=d7e81d1feead1dec1a7a0a4c71b24ef8&type=album)

![Alt-example](https://sun9-65.userapi.com/impg/zIneVHHNPqGLHhm6IUjxdtz7OVUvG-yUJ7-9FQ/We0T2kGELSo.jpg?size=294x100&quality=96&sign=1399e1f3b1521cf7458a275c3bdf1637&type=album)

## GIT

`Git init` – создать локальный репозиторий в папке проекта

`Git add .` – добавить все файлы проекта 
`Git commit -m “текст коммита”` – сделать коммит

`Git status` – посмотреть состояние добавленных файлов и увидеть если ли файлы которые были изменены

`Git log` – история коммитов

`Git diff имяфайла` – посмотреть разницу содержимого файла между разными комитами

`Git checkout имяфайла` – изменить файл на последнюю версию коммита этого файла

`Git remote add origin ссылка на удаленный репозиторий` – подключится к удаленному репозиторию

`Git push -u origin master` 
Где master – имя ветки 
Origin – имя удаленного

DC_Store – настроичный файл который сохраняет текущие вещи которые располагаются в папке проекта

`Touch .gitignore` – создается файл в который будет добавляться другие файлы чтобы они не отправлялись на удаленный репозиторий

Внутри .gitignore пишем название файла которые хотим чтобы оно игнорировалось – не добавлялось в коммиты – с помощью любого редактора кода

Чтобы комментировать внутри .gitignore – использовать #Комментарий
Чтобы указать расширение на игнорирование всех файлов для коммитов – использовать *.расширение

`Git rm –cached -r .` – удалить все файлы которые были добавлены после git add .


`Git clone ссылкана репозиторий` – скопировать репозиторий на диск

`Git branch имяветки` – создать новую ветку

`Git checkout имяветки` – перейти на другую ветку

`Git merge имяветки` – соединить две ветки – затем открывается текстовый редактор где можно оставить комментарий, чтобы из него выйти - q!

Чтобы загрузить последний коммит в xcode – Source control – Discard all changes

Чтобы создать новую ветку с точки коммита – выбрать в ветке master коммит – branch from цифрыкоммита

Чтобы переместиться на другую ветку – нажать на ветку – checkout

Чтобы соединить изменения в ветки в ветку master – переключится на данную ветку – выбрать master ветку – нажать merge имяветки into master

Чтобы другому человеку работать над проектов на github – зайти на репозиторий – нажать на fork – сделать изменения – в добавленном репозитории нажать new pull request – create pull request – на аккаунте который создал изначальный репозиторий нажать на merge pull request – confirm merge

![Alt-example](https://sun9-59.userapi.com/impg/zt6SIPFz6gRSamGSwh2V9DvhjwDYDSTzcdc6Tw/3O81KlxE0hk.jpg?size=936x510&quality=96&sign=3744951f260f591bc3f1de582bddb330&type=album)

## CoreImage

`Import CoreImage`

![Alt-example](https://sun9-72.userapi.com/impg/geAOSUiKEpowcEhkmIArPzJ621GLejXJehSkpw/p4mRdvmNtAc.jpg?size=418x100&quality=96&sign=c865eb83abaa6c4c7e570977ad72c361&type=album)
 
CIContext – захватывает рендеринг

CIFilter – записывает какой филтер пользователь активировал

В методе `ViewDidLoad()`:
 
![Alt-example](https://sun9-9.userapi.com/impg/pO-PCFV2O96wr2aQ4POW99r6puyco94U-i1qaQ/d_a21EH7PMA.jpg?size=618x86&quality=96&sign=6d27378be04413fe3d9b92011d143ab7&type=album) 
 
Филтер принимает sepia tone effect на изображения

Так как в примере идет работа с выбиранием изображения то в методе didFinishPickingMediaWithInfo:

![Alt-example](https://sun9-75.userapi.com/impg/6zpHOsT-QGAE6HGChlmcXhkl5_1jMRap5BKopw/GokQVyz23UM.jpg?size=728x284&quality=96&sign=76c31107dce30370082f21905e8e6b92&type=album)
 
Создаем CIImage из UiImage и отправляем результат в текущий Core Image Filter используя ключ

![Alt-example](https://sun9-35.userapi.com/impg/VwzTgUlRbwQMgXteBP19OCkee2W8WDsQkcQU-Q/vvReP7AJvGk.jpg?size=936x218&quality=96&sign=f70da32d04a78be75150a89ae1cd2eeb&type=album) 
 
Intensity – параметр picker-a

`.extent` – означает что вся часть изображения будет рендериться

Меняем applyProcessing на выбор несколько редактируемых методов с помощью ключей:

![Alt-example](https://sun9-35.userapi.com/impg/Da-Dr6vV16BK47-gB_REHqudsbwqFO-joAXopg/NvOBUFKbfL0.jpg?size=736x498&quality=96&sign=1f4bfd3227a7da7214cb954772e5efb0&type=album)

## UIImageWriteToSavedPhotosAlbum

Записывает изображение в фото альбом

Данный метод содержит 4 параметра:

1.Изображение которое будет сохранено

2.Кто вызывается когда запись будет закончена – self – the current view controller

3.Какой метод вызывается - selector

4.Любой контекст

![Alt-example](https://sun9-84.userapi.com/impg/m65t5kDXS5npbsOxPnuvQhnWRxHq-1pfVN_3Qg/11mQC_jvSRM.jpg?size=936x162&quality=96&sign=676a13f9f3cd69ef5466d9b4de3e4db3&type=album)
![Alt-example](https://sun9-80.userapi.com/impg/suudCsZwmbnAsk36UHdMP7AnPGxp63tZyMaguA/FkjZBF8KMe4.jpg?size=936x422&quality=96&sign=6f2f584778a7d107e37abe120ed2dcca&type=album)

## Animation

CGAffineTransform – структура которая представляет специфичные методы трансформации которые могут быть приняты на любой UIView объект или класс

Увеличить размер в 2 раза:
 
![Alt-example](https://sun9-78.userapi.com/impg/RMI33ERo4s_JumnLehZnAhvPB3G7Zq31c2HARA/2Fv0mUuKS-c.jpg?size=874x154&quality=96&sign=f691a948e1c4b4680435fa531ef87f75&type=album) 
 
.identity – очищает все трансформации и сбрасывает все изменения которые были установлены
 
![Alt-example](https://sun9-37.userapi.com/impg/Ltjwm7t3m1mUw2lWTtRItuvTikDQlrnStSvgmA/7kCrxJ70YJI.jpg?size=824x66&quality=96&sign=21c722919a0e97180292feb4bc24e4ba&type=album)

Чтобы переместить объект в другую точку:
 
![Alt-example](https://sun9-25.userapi.com/impg/BFdizyHjqWNpvfk3Y7XzMP1PpihsNrPl4qTO-A/Il3HwkJvIAY.jpg?size=936x64&quality=96&sign=db496d8133506381787483787150160d&type=album)

Координаты начинают отсчитываться от точки объекта

Чтобы вращать объект:

![Alt-example](https://sun9-5.userapi.com/impg/n_yKuVTuP8QxLgPAO4jk9YNiuaz4hh250B8zyg/3yywAfx6rzg.jpg?size=936x64&quality=96&sign=a7cf0880cf8bf96b167dddf88e25bd7d&type=album)

Значение в радианах указано в CGFloat
Если вращать на 90 градусов то Core Animation высчитывает всегда короткий путь поэтому будет по часовой, а если вращать на 270 градусов то будет вращаться против часовой
Также работает если указать 360 градусов то вращения не будет, а если 540 градусов то вращаться всего будет на 180 градусов

Также можно добавить в анимацию изменения прозрачности объекта и изменение фона:

![Alt-example](https://sun9-78.userapi.com/impg/S4AR1p4gjHUOOY2n9xMbXkf7kbI-stQVTEDlng/QC72Sa3LEbU.jpg?size=812x206&quality=96&sign=2c26b693099bf7181bd3057e0ba5db33&type=album)

Чтобы добавить пружинитости при анимации объекта: usingSpringWithDamping и initialSpringVelocity

![Alt-example](https://sun9-57.userapi.com/impg/dizVjnetFMYVeYNyzcQAWO069T1ntqH5Toowow/OxUzu8OPUzg.jpg?size=936x62&quality=96&sign=4973d4abf8b197078feadf0d989dcfb6&type=album)

## Segue

Чтобы создать переход от одного вью к другому – выбрать вью через control и перетащить на желаемое вью которое будет показываться при переходе – выбрать show – справа установить идентификатор перехода
В коде написать performSegue:

![Alt-example](https://sun9-42.userapi.com/impg/5l7Zz659dXxxz_lnOTodh0EY0PDReMXJiRBadQ/TO7ivip8mxo.jpg?size=936x76&quality=96&sign=b4880500e137ce37da1f63a4e83795bd&type=album)

Первым аргументом указываем идентификатор который написан на переходе

Чтобы отправить значения от одного вью к другому при переходе – использовать override func prepare :

![Alt-example](https://sun9-44.userapi.com/impg/LWv8NqQ_QVxE52J7c7IJ3eaMUDMVuv_YrptUcg/Ldrr7pfCTx4.jpg?size=936x192&quality=96&sign=a96ed79a5a9025602ac72969b3fffdef&type=album)

Делаем проверку на идентификатор перехода так как на одном vc может быть разные переходы с разными идентификаторами
Также инициализируем vc как название класса данного vc

## MapKit

Ищем MapKitView в библиотеке и вставляем, не забываем установить delegate mapView – для этого 

`Import MapKit`

Аннотация – объект который содержит title, subtitle , position которая вызывается CLLocationCoordinate2D – структура которая содержит долготу и широту где аннотация должна быть расположена – для этого подписываем класс на протокол MKAnnotation, при этом класс также должен быть наследовать NSObject

![Alt-example](https://sun9-82.userapi.com/impg/J2PnSGo4pMtQDBo3iks7fInuVfMc4GuYq_mSiA/xpxve_VBLl4.jpg?size=488x408&quality=96&sign=208d371930ffd7bfa08526ec01ceef2b&type=album)

`.addAnnotation()` – добавить аннотацию на карту
`.addAnnotations([])` -  массив аннотаций

![Alt-example](https://sun9-1.userapi.com/impg/5gEdcdxaMjvUAGzxj7JcxwR56doCIy_E5GFQgQ/TL6hvHimfWE.jpg?size=650x280&quality=96&sign=631ac9b5aab7c480e3a0b2683768e015&type=album)

ViewController с mapView оутлетом должен наследовать MKMapViewDelegate

![Alt-example](https://sun9-10.userapi.com/impg/sYxDPblNCamR619-uy7PJcPCOi7_k4esYPGQBg/EGTrQJYA5gc.jpg?size=836x654&quality=96&sign=a25210bde2985e2d3d025ee4465764ed&type=album)

При нажатие на кнопку аннотации map view отправляет сообщение делегату

Нужно проверить аннотацию на принадлежность к нашему кастомному классу так как при использовании геолокации нужно возвращать nil если аннотацию не принадлежит кастомному классу

Нужно установить переиспользоваемый идентификатор – строка которая будет использоваться для гарантировании что переиспользуется аннотации 

dequeueReusableAnnotationView – используется для экономии памяти, достает неиспользуемые аннотации 

`.canShowCallout` – показывает title и subtitle аннотации при нажатие

`.detailDisclsure` – синий i внутри круга 

Можно изменить тип карты - `.mapType`

## WebKit

![Alt-example](https://sun9-44.userapi.com/impg/uFW4myulrznJ7XOtwntgmteDDlsCgF0DoswO3g/BLgxuP_vcB0.jpg?size=496x378&quality=96&sign=09136e63a98f3b960d987cd27d4942dc&type=album)

`.allowsBackForwardNavigationGestures` – позволяет пользователям переходить между страницами сайта назад и вперед

Создание кнопки с выбором сайтов и переходом на них:

![Alt-example](https://sun9-50.userapi.com/impg/-zMBl323rXygidcaBfXWycTA8oh6QXOruuZutw/s4FWDd2Kaes.jpg?size=746x480&quality=96&sign=4de9a43dffad3eca5079ee0249f0d0ce&type=album)

Создание refresh кнопки, линии загрузки страницы с помощью UIProgressView и свободного пространства в toolbar:
 
![Alt-example](https://sun9-66.userapi.com/impg/fV6CiBUNEeZtk3AnLbokMFCCM34sTDg2ebI_ZA/jPj_5hXyHfQ.jpg?size=622x492&quality=96&sign=98b4cf3324c38348273f489c228cbf17&type=album)

UIProgressView – показывает на UIBarButtonItem прогресс загрузки страницы

![Alt-example](https://sun9-17.userapi.com/impg/ysdicD4jiT9RBfULXq-tBou0s1Ifu-hCIA_DTg/NE7b0O9AFdU.jpg?size=624x494&quality=96&sign=255a2efad0f1b37036d93fbe6635a3ae&type=album)

## Debugging

В методе `print(1,2,3,separator: “”)` второй аргумент вставляет строку которая будет находится между каждый элементом
В методе `print(1,2,3,terminator: “”)` второй аргумент вставляет строку после конца элемента

Assert – проверки для отладки которые приводят к сбою приложение если определенное условие не выполняется

`assert(1 == 2, "Math failure")`

Если проверка окажется ложной то приложение прекратить работа с выводом ошибки которую мы написали во 2 аргументе

Данные проверки никогда не выполняются в реальном приложение потому что Xcode их убирает

Чтобы сделать следующий шаг в breakpoint – fn+f6

Чтобы перейти к следующему breakpoint – control+cmd+Y

Также можно установить на breakpoint условие его выполнения – нажать правой кнопкой на breakpoint синий – edit breakpoint – в condition написать условие остановки

Чтобы приостановить выполнение когда появляется исключение – cmd+8 – снизу слева нажать + - выбрать Exception Breakpoint

Чтобы увидеть 3D представление экрана – запусить аппку – debug – view debugging – Capture View Hierarchy

## Safari_extension

Отправляем данные из safari в extension

Создать новый extension – file – new – targer – ios -application extension – action extension
В Action Type установить Presents User Interface

![Alt-example](https://sun9-1.userapi.com/impg/cL6XM-QahSeAql67pdLoi012ic2m5CKG23r52A/Am4x1m1ezMQ.jpg?size=936x202&quality=96&sign=a988696d716341005c7f92a81aa2ba80&type=album)

Когда создается extension  то extensionContext позволяет контролировать как взаимодействовать с родительским приложением

Inputitems – массив данных который отправляется родительским приложением в extension

Входящие данные содержат массив attachments

В info.plist в NSExtension – NSExtensionAttributes – NSExtensionActivationRule меняем со string на Dictionary – в этом же нажимаем на + и вставляем NSExtensionActivationSupportsWebPageWithMaxCount и справа пишем 1 – это означает что будет получаться только web page, без изображений и других данных

Далее в NSExtensionAttributes нажимаем + и добавляем NSExtensionJavaScriptPreprocessingFile а справа пишем Action – это указывает IOS что когда extension вызывается нужно запустить JavaScript предотварительные файлы c названием Action.js (.js не пишем так как IOS сам вставляет)

![Alt-example](https://sun9-21.userapi.com/impg/4rQK7t7NlfdFBLa-QnMM4xHwarHNue5ZXSxKxg/PqfmV8-Tt2M.jpg?size=798x260&quality=96&sign=4e3dfad002f20c2d56941ab352ac997a&type=album)

Чтобы создать Action – правым кликом кликаем на info.plist который в extensions файле – new file – other – empty
 
![Alt-example](https://sun9-77.userapi.com/impg/qRZdOB7MtMRm2ai_wuY9cPFZSc0QXX6Rl0rqdA/aXBSLIslOuY.jpg?size=936x272&quality=96&sign=24234d549f27c75845096ddf1853dbad&type=album)
 
Первая функция вызывает до того как extension запуститься а другая после

В методе viewDidLoad:
 
![Alt-example](https://sun9-59.userapi.com/impg/jGfC1KrSqWW9RodPJIGiNSRnjyINbUGKr2sHEA/93JLrGG9tDE.jpg?size=936x128&quality=96&sign=e0b14a8e8666df9b762960a7a72aec04&type=album)

NSDictionary – как и dictionary только в нем не объявляется тип и соответственно нельзя узнать какой тип данных хранится

В mainInterface вставляем textView и убираем настройки которые отвечают за корректирования текста :
 
![Alt-example](https://sun9-61.userapi.com/impg/sHTdCO4roEQCmF8xjwcdzT66WEQM5079ou3yjw/j617lqB73m0.jpg?size=492x206&quality=96&sign=8dfd836a32ebbbbef18d958ffff3a000&type=album)

![Alt-example](https://sun9-58.userapi.com/impg/4L53zp6fNGPOQvQfBtnSKulYDuXWJ7BJcW5bgQ/qIiulnCgF5Y.jpg?size=712x520&quality=96&sign=cd5266f16805fec7c09ec0c10b00c35f&type=album)

![Alt-example](https://sun9-29.userapi.com/impg/d40ETu_ylm_9g3P98gAOnTo_KxDkQUfSgXmOfw/CpzPC_N1E2E.jpg?size=660x152&quality=96&sign=bf41020f94ce8d14dded45c2a5c7bd07&type=album)

![Alt-example](https://sun9-36.userapi.com/impg/cdQfjIb0Ie6-UgTiOCLq5J3_bNe1QwFGYghnOg/bcevonyU8WE.jpg?size=936x634&quality=96&sign=d5012a46b856d2796a2bf0a6b525e1ae&type=album)

Данный код нужен для отправки данных обратно в Safari

![Alt-example](https://sun9-53.userapi.com/impg/1zPnze86cP3wUrikKL7k-fBafALeDTFxVvEWag/fBji13d266I.jpg?size=894x174&quality=96&sign=b86e610ece80bf412d90d4a7b4dcd0ed&type=album)

Извлекаем значение customJavaScript из массива параметром передаем его функции eval() которая выполняет любой найденный код

Запускаем extension через safari – заходим например на сайт apple – снизу выбираем значок отправки данных – ищем extension – вводим alert(document.title); - получаем алерт с названим страницы

## Keyboard

keyboardWillHideNotification – отправляется уведомление когда клавиатура показывается 

keyboardWillChangeFrameNotification – отправляется когда состояние клавиатуры изменяется

addObserver() – зарегестрировать нас как observer для уведомлений, имеет 4 параметра:
1.объект который будет получать уведомления – self
2.метод который будет вызываться 
3.уведомление которое мы хотим получать
4.объект который мы хотим наблюдать – если установить nil то это означает что не имеет значения кто отправляет уведомления
 
![Alt-example](https://sun9-41.userapi.com/impg/xUCr1GEiee7Pt4Ncowv4JiTi13vGbweYUiTjyw/lx-cQNlAiI0.jpg?size=936x246&quality=96&sign=be20126fa5591a465f49c583f99235a2&type=album)

![Alt-example](https://sun9-63.userapi.com/impg/VuYOwwGY-svTpZ944yKhSFkLRIFP9Lg1t151rg/M_aT3E_a9xc.jpg?size=712x72&quality=96&sign=1f425b5bc4aadf5e0ecebc4c7732658b&type=album)

![Alt-example](https://sun9-9.userapi.com/impg/ntSc3_u0azsiD_YTWkwDUk9FiqvxaquNvZcEnw/iMGJKcuRatI.jpg?size=936x422&quality=96&sign=053696b2a79c4879b577e691be83a5fd&type=album)
 
Notification включает имя уведомления как Dictionary содержащий информацию о конкретном уведомление называющееся userInfo

UIResponder.keyboardFrameEndUserInfoKey – содержит информация о размере клавиатуры после того как она закончила появляться, которая является типом NSValue которая в свою очередь относится к CGRect(данная структура содержит CGPoint и CGSize поэтому это может описать прямоугольник)

Так как в objective – c массивы и словари не могут содержать структуры по типу CGRect то Apple сделала специальный класс NSValue чтобы можно была вставлять их в массивы и словари

Если пользователь находится в альбомном режиме используется метод convert()

contentInset и scrollIndicatorInsets – делают отступ по краям текстового представления даже если ограничения от края да края

## UNUserNotificationCenter
Import UserNotifications

Создаем запрос на разрешение использования уведомления:

![Alt-example](https://sun9-54.userapi.com/impg/2mGkbKUC9NcEtjl4hTyKh4COAN6cWKC1Dd9mrw/pqDWxnZR47M.jpg?size=936x70&quality=96&sign=c3c5fb32b8c478ebe0a59b62baec91d8&type=album)

Создаем повторяющиеся уведомления каждое утро в 10:30:

![Alt-example](https://sun9-47.userapi.com/impg/YVlP2F-lAy8oBUEQjciq9oFH8JFtSf-fEzncyg/emSSMvQCp4U.jpg?size=924x208&quality=96&sign=279788e13e984ddedc45ea6b6889a7a4&type=album)

Создаем контент который будет на уведомлении:
 
![Alt-example](https://sun9-37.userapi.com/impg/tfkcIEtI5Upvv7AfVHvwVu-86vytsi8iB1QOKQ/1-FEl24gQYk.jpg?size=742x208&quality=96&sign=19994043bff6459a949e13dd33e34199&type=album)

Делаем запрос:

![Alt-example](https://sun9-23.userapi.com/impg/PG7vUOh6R2dootvV_9Rgqokp0bXg51HnRm-9Eg/vkZBnBWRd5M.jpg?size=936x96&quality=96&sign=efc73752603056136afe9b72ef4afd78&type=album)

Отменить все уведомления которые находятся в ожидании:
 
![Alt-example](https://sun9-85.userapi.com/impg/hOKunDSKh7Ny83zyCZUjPtb8Vmqgzh_50h-WzA/IXpSfYca63E.jpg?size=936x82&quality=96&sign=3a98c76a82be5013617f3135babb0a99&type=album)

Уведомление которое появляется через 5 секунд:
 
![Alt-example](https://sun9-34.userapi.com/impg/QSsqhGeD38vVTzj3MSImdIQmy30HJnIZrngzKg/HJbUicgbCJE.jpg?size=936x66&quality=96&sign=117b581baecd1f503ee215a2d55dc6c8&type=album)

UNNotificationAction – создает индивидуальные кнопки для ответа пользователя на уведомление
Первый аргумент – уникальная текстовая строка которая отправляется когда кнопка нажимается

UNNotificationCategory – группирует много кнопок вместе под единственным идентификатором

Также класс должен наследовать UNUserNotificationCenterDelegate

Создаем кнопку которая будет снизу при свайпе уведомления влево и нажатия на кнопку View когда девайс заблокирован:

![Alt-example](https://sun9-16.userapi.com/impg/lzrBrOPslhbyCTzoxk__Sdktkn2t4cdyDK9O2g/nK104jv-OEw.jpg?size=936x240&quality=96&sign=d57e754b2b3f38fb4fc4ae644d652920&type=album)

UNNotificationDefaultActionIdentifier – отправляется когда пользователь смахивает уведомление чтобы разблокировать свое устройство и запустить приложение

![Alt-example](https://sun9-42.userapi.com/impg/eSR4FJEO1kKApNh3pgjlj6xrDMu_OS3bOLcySQ/wyTBPsE8RWs.jpg?size=936x448&quality=96&sign=5295ce8a37f6885251404400dbb3cce5&type=album)

## Create_custom_color_or_vector_image_switched_with_dark_mode

Чтобы кастомный цвет менялся также как и системный цвет при смене темы например со светлой на черную – в assets нажать снизу на + и выбрать color set – справа в appearances выбрать any, light, dark – выбрать цвета для всех 3 тем 

Чтобы установить векторное пдф изображение – в assets добавляем данное изображение в пдф и справа в resizing ставим галочку – в scales выбираем Single Scale -–в appearances выбираем any light dark чтобы установить разные изображения для разных режимов

## Protocols

- перечень требований которым должен удовлетворять тип данных соответствующий ему
Также содержат реализацию, перечень свойств, методов и сабскриптов которые должны быть реализованы в объектном типе

![Alt-example](https://sun9-67.userapi.com/impg/JeBqN6i7Os88pToQRL5jo3VUyEbMMNm5s7-WhA/dL9i35KHSmw.jpg?size=346x100&quality=96&sign=2715f008ec565d8962610db73b5b119f&type=album)
 
![Alt-example](https://sun9-58.userapi.com/impg/1aL51_HCcQXzhSUo4zPvNOT0j2sIeAmRvdkB7w/eqVmQk6DCns.jpg?size=814x486&quality=96&sign=ca84953e1b1b64cce2b87759eb8d1f72&type=album)

Свойства в протоколе:
 
![Alt-example](https://sun9-63.userapi.com/impg/ApTreVGTlpVqvNAl1LZguVversBnK6BmWW4WKQ/UlPGHO_ghCw.jpg?size=754x154&quality=96&sign=8692b4779cab92ffe5393c85801e70ec&type=album)

![Alt-example](https://sun9-79.userapi.com/impg/X54N7htidOhaMhK6rgITIoB2zwKgcRJOeBVRsQ/q5Fj1C6xlA4.jpg?size=936x296&quality=96&sign=9d8c287427d4d6201bd2e28a7ba72ec8&type=album)

![Alt-example](https://sun9-5.userapi.com/impg/V_czHams_eP4hOPLst8LaTyaOEqQQ_OZx-qEbA/Gw1MQSiNWFA.jpg?size=936x310&quality=96&sign=dfc08a28889f970f44d3c569f567ce3e&type=album)
 

Тип обязан реализовать все что прописано в протоке при этом реализация не ограничивается свойствами протокола:
 
![Alt-example](https://sun9-85.userapi.com/impg/p9Ur3n1En8ScrJ7tTCZbfWYxhPOYDqqHikbIYA/mq1VhubrUJw.jpg?size=936x310&quality=96&sign=18661a3e3b04fe11484ec0396f7277ba&type=album)

Чтобы обязательно реализовать свойства типа используют static:
 
![Alt-example](https://sun9-8.userapi.com/impg/actWSTvXfH0lZ8c8uLGzyJhVBJj18K5QIJBIpA/7bY-pNsajQo.jpg?size=592x100&quality=96&sign=36a90267f42d3a5f6062a2b9f878542f&type=album)

![Alt-example](https://sun9-75.userapi.com/impg/KEnB0kCGj4XcWoeyghHjnD82ZilLARNrt45gaA/2SfspZ0S8xs.jpg?size=482x154&quality=96&sign=37a098a016f8dc679f81feafc4971f62&type=album)

Методы в протоколе:
Для требования реализации метода -static а для изменяющего метода -  mutating

![Alt-example](https://sun9-30.userapi.com/impg/aiShy8vYHxn9LzK1OwL9utB3y66Xoo1-0swsaQ/j0tAdiIQqUs.jpg?size=776x164&quality=96&sign=e8fd46b73f955c6042741d90188a22e0&type=album) 
 
![Alt-example](https://sun9-11.userapi.com/impg/4x99JH3dj9nJX66lpAtBlaAwrC-EtbkXJglprQ/I6NHadHfxXI.jpg?size=868x568&quality=96&sign=06be4d29a56bb1db6f469d7d0ffc1ace&type=album)

![Alt-example](https://sun9-79.userapi.com/impg/tgwiYfDepswvAk-yolKSleNU6JRx0VMUV-JJrw/o_WzJvaRSKE.jpg?size=646x170&quality=96&sign=02102a7f18807d94c227a78f9a7ba7d5&type=album)

Инициализация в протоколах:
Перед объявлением инициализатора протокола в классе необходимо указывать – required – но также в классе могут быть свои инициализаторы
 
![Alt-example](https://sun9-34.userapi.com/impg/E5wUwK14CY9NSpJRy8mswVpI6LjaQgGUTyt-qQ/awNcRiYT1bU.jpg?size=454x292&quality=96&sign=37b1381205371e4917af3b44aa937e10&type=album)

Протокол может выступать в качестве типа данных для значений
Протокол может указывать на множество типов:

![Alt-example](https://sun9-79.userapi.com/impg/F2kLOcv6KZWfn7vF3EOS2qoMcPXWs4IGIYG90Q/H7QFmKsTCTM.jpg?size=652x88&quality=96&sign=2db26c99f28392053421c27730d73b0d&type=album)

![Alt-example](https://sun9-8.userapi.com/impg/SI915KRmFKY3cFrKtewfpHXGTPVVjKMjnAGXIg/y9J-r07-A38.jpg?size=284x74&quality=96&sign=1f95eff5413b6d4c133c35a212fc7757&type=album)

В данном примере функция принимает любое значение типа T где тип T должен соответствовать протоколу данному

Перебор элементов коллекции с помощью as для поиска значения определенного типа протокола:

![Alt-example](https://sun9-81.userapi.com/impg/P4LQenRHQ2Vvu6vARue9AaCLLL2XMDBX-r7PgA/WeiFOwd7ZNs.jpg?size=334x86&quality=96&sign=e5b4b33fb95f76b0297a3af69b12a01a&type=album)
 
![Alt-example](https://sun9-49.userapi.com/impg/1W-IvwFZPO76_0PMoKdXQzOpG4-EalKmXjPtkQ/5R5CzRCCdeE.jpg?size=340x406&quality=96&sign=8b0c954218a398938a256646eacfd89b&type=album)

![Alt-example](https://sun9-32.userapi.com/impg/yecjpvhzZwuMuAWTAJorJ_8LVUPBEwP4Hi5TTA/SZdxVmw-EsA.jpg?size=428x174&quality=96&sign=03862cc50d61a0b1cbec0bc40e5a8faf&type=album)

Проверка соответствия типа при помощи is :

![Alt-example](https://sun9-59.userapi.com/impg/7BwZbxs31EsB-iOYSnDRx5faU7tZLyxj5-5CAQ/PzxAQtRYl_Y.jpg?size=410x318&quality=96&sign=1d9c6454b800722e1d4b875ea00274fb&type=album)

Наследование протоколов:
Протокол может наследовать один или более других протоколов при этом все требования будут добавлены в него и также можно добавлять дополнительные требования 
Если значения принимает тип протокола то оно должно выполнить все требования всех протоколов которые были наследованы 
 
![Alt-example](https://sun9-28.userapi.com/impg/QX0ahl11FOYHkflps9JLoOu1nWc83yu1Huoq-A/GZHmQPDuIeE.jpg?size=658x588&quality=96&sign=6a002dd8703c24017016dbe61d6d74d9&type=album)

Чтобы ограничить протокол только на классы – написать class после имени протокола через двоеточие после пишутся родительские протокол

![Alt-example](https://sun9-64.userapi.com/impg/wSNCWHXa1hUPnRlHVL9OuHRZtPAAAnEQ1To3pQ/ysYvZ9cfD9w.jpg?size=614x136&quality=96&sign=6d966a7b4902f8f801507fe5dc8d6b26&type=album)

Композиция протоколов:
Комбинация нескольких протоколов чтобы требуемый тип данных соответствовал множеству протоколов

![Alt-example](https://sun9-86.userapi.com/impg/JfX_Z5FZmxWBQCqoDXsw_PG_7wesbBo__JzT2Q/p3dDWpoe92A.jpg?size=408x102&quality=96&sign=7f341b3d5e1e26d91985fea611d01f0f&type=album)

![Alt-example](https://sun9-60.userapi.com/impg/NolEWH8TmfM-3t_yt0Ho7espkNc-Mwh78NnX1Q/IwByJ0Oibo0.jpg?size=936x594&quality=96&sign=8aea976daedb0a0d21d88bd91f147cb7&type=album)

## Delegate_Design_Patterns

## API

## UITextField

Чтобы изменить тип клавиатуры который будет выдвигаться при нажатие – справа в text input traits выбираем нужные настройки 

Чтобы пользователь при вводе не видел символы например для пароля – справа в secure text entry ставим галочку

Чтобы кнопка search на клавиатуре делала какие – то действия – класс должен наследовать протокол UITextFieldDelegate, также:

![Alt-example](https://sun9-19.userapi.com/impg/wF9OD4y922MrgW4a7L1kJnpWjIbOYMmwiWramg/8mhHWow8i4M.jpg?size=840x190&quality=96&sign=2b62fd60e8b2bfccbcdd55ab1e5c4260&type=album)

И только затем можем использовать метод textFieldShouldReturn в котором пишутся действия при нажатие на кпопку search на клавиатуре

Чтобы клавиатура скрывалась – searchTextField.endEditing(true)

Чтобы автоматически текст удалялся после скрывания клавиатуры:
 
![Alt-example](https://sun9-84.userapi.com/impg/Zf5QZa22DY9lPk2cLDJjxOBQek1le_W5TVLWOQ/Wkc6VIShNJI.jpg?size=774x98&quality=96&sign=4407bb7e31d2c6e8f59345a6ceb8ab07&type=album)

Метод textFieldShouldEndEditing позволяет пользователю не закрывать клавиатуру если он ничего не написал:

![Alt-example](https://sun9-5.userapi.com/impg/dqW9wLwNqdgFnEwg2oYZd7oVBmmEXHaAN62BWw/2wqZbvPeuYE.jpg?size=936x266&quality=96&sign=db648bee814783a92db121e7065a1a50&type=album)

## MVC

Controller – берет информацию из Model и трансформирует ее во View

В Model находится логика

В View находится расположение отображения объектов

![Alt-example](https://sun9-88.userapi.com/impg/eA-pjADQolEzIKfMrD6G3OY9XV0tuGldVsuLjQ/LPkKwpI2vco.jpg?size=514x330&quality=96&sign=55f5c9d47c906a863d3fe29cd6164314&type=album)

![Alt-example](https://sun9-18.userapi.com/impg/bc3vJmK8F2i79FXZaBoIT8Aa-txyUn8q0CIxlg/IMtnCqN7b9k.jpg?size=446x270&quality=96&sign=6eb92d7a273a24ff39b75835cc3a87d1&type=album)

![Alt-example](https://sun9-76.userapi.com/impg/FPfk3NT75B6HwS_MpNQCyJODnKzyuXwfh84Xnw/0uU0mTs_Unk.jpg?size=552x288&quality=96&sign=f2a27e6b73e609519f9ab5c39aeb8461&type=album)

Models – структуры и простые классы
Views – отображают визуальные элементы, сабклассы UIView
Controllers – координирует между models и views, сабклассы UIViewContoller

Распорядок по папкам:

![Alt-example](https://sun9-3.userapi.com/impg/CsrtpF_lQOmSSwjyZDdAMEsu29CSEmA_9m4pwg/wMESJqkt0zA.jpg?size=260x430&quality=96&sign=2883a6bab9c89e89667fc2e18a151d91&type=album)

Model:

![Alt-example](https://sun9-13.userapi.com/impg/wmh4XTqQX7gUGqEf-cYLRm8JQKmxnrrhBdFlyw/3CgMPy9ENs0.jpg?size=360x142&quality=96&sign=6681f158078b940142fb3fde052cb63b&type=album)

![Alt-example](https://sun9-80.userapi.com/impg/bfYybSp2hQw_n2vcQrthI4ezxD-nFJpY3TRZIg/hIXhsluw_ps.jpg?size=412x114&quality=96&sign=08f8de53f9a6d9ef293eaeff43d2b4e8&type=album)

![Alt-example](https://sun9-78.userapi.com/impg/F_nM72pGFVHXCKYEauyQlTLtV9AgOgVlYwC6_A/oX4Xh-UTzsA.jpg?size=440x98&quality=96&sign=713a62bc2b942a518526a689e3cac3b3&type=album)

![Alt-example](https://sun9-45.userapi.com/impg/2qqPhO_8yuX3uw2GXrPusnE9fDljqRMNj2gR5A/JU7yf7F2KYI.jpg?size=682x252&quality=96&sign=ca9a9ef79ddfa5786caa11805247fc59&type=album)

View:

![Alt-example](https://sun9-68.userapi.com/impg/ehgQGte2bHEqSXqa_NPXONJvUQxfsFyYjs5Mhg/QR_mF2UGXZY.jpg?size=644x218&quality=96&sign=177e9d3a625bd642011aabcd3367a9b3&type=album)

ViewController:

![Alt-example](https://sun9-10.userapi.com/impg/TTR9oSdb8sBDyIFDp2P81Ad4bIg6GKcWXkM0Hw/5drNmW0JL4E.jpg?size=634x754&quality=96&sign=d69ac48808a1aa1fabaaffbca5a696b9&type=album)

![Alt-example](https://sun9-14.userapi.com/impg/VarH2I-n-Y45O6nFr69-U0Dvz9L3fFEHnNtWmQ/C8ku6LYEXC8.jpg?size=618x282&quality=96&sign=123b78577fe3ce0c5bc9fc6f06a3fb2d&type=album)

## API

## Map

