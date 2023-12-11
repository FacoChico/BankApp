# Мобильное банковское приложение
<!-- ABOUT THE PROJECT -->
## О проекте
Проект сделан в процессе прохождения курса "Технология разработки программных приложений" РТУ МИРЭА.

В состав команды входят:
* Пеньшина Дарья Сергеевна
* Попов Григорий Павлович
* Пронкина Александра Георгиевна
<!-- GETTING STARTED -->
## Немного о начале разработки
Перед началом разработки проекта были выдвинуты требования (бэклог), которым он должен обязательно удовлетворять:

1. Приложение должно полностью имитировать основную работу реального бонковского приложения;
2. Главный экран приложения должен содержать основную информацию о счетах, а также инструменты для совершения пользователем дальнейших действий;
3. Необходимо предусмотреть возможность смены пароля учетной записи пользователя в целях обеспечения безопасности;
4. Названия кнопок, иконок и полей должны соответствовать тому, что происходит в процессе взаимодействия пользователя и системы;
5. Дизайн - нейтральный.

Как и в любом процессе разработки программного продукта, в процессе разработки данного приложения была предусмотрена возможность вносить правки в бэклог прямо "на ходу", т.к. во время работы приходят новые идеи, меняются мнения относительно реализации определенных программных модулей и функционала в целом.
## О платформе
Самой удобной формой реализации для проектов такого рода является мобильная, исходя из чего было решено разрабатывать приложение на Java в Android Studio под Android 5.0 и выше (для совместимости с большинством современных устройств на базе Android). Язык разметки - XML. Используется система сборки Gradle.

У каждого из членов команды имеются свои ***второстепенные*** роли:
* Пеньшина Дарья - дизайнер, скрам-мастер, фронтэнд разработчик;
* Попов Григорий - в основном бэк-, частично фронтэнд разработчик;
* Пронкина Александра - частично бэк-, в основном фронтэнд разрабочик.

Но у всех одна ***основная*** – разработчик.
## Зависимости
Зависимости, используемые в проекте, представлены ниже.

dependencies {

    implementation 'androidx.appcompat:appcompat:1.3.0'
    implementation 'com.google.android.material:material:1.4.0'
    implementation 'androidx.constraintlayout:constraintlayout:2.0.4'
    testImplementation 'junit:junit:4.13.2'
    androidTestImplementation 'androidx.test.ext:junit:1.1.3'
    androidTestImplementation 'androidx.test.espresso:espresso-core:3.4.0'
    implementation 'pl.droidsonroids.gif:android-gif-drawable:1.2.25'
}
