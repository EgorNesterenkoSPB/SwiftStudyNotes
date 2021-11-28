# SwiftStudyNotes :octocat:
# Topics with some information to repeat or remember the theme :heart_eyes_cat:
![Alt-userD503](https://quickbirdstudios.com/blog/wp-content/uploads/2019/11/Swift-1.jpg)
- [Swift](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#Swift)

  - [MVC](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#MVC)
  - [GCD](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#GCD)

- [SwiftUI](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#SwiftUI)

  - [LifeCycle](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#LifeCycle)
  - [AVAudioPlayer](https://github.com/EgorNesterenkoSPB/SwiftStudyNotes#AVAudioPlayer)
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

## MVC
