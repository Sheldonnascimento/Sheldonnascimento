XCODE: https://developer.apple.com/download/
RVM: 2.3.0 / Rbenv
HOMEBREW:
Ruby
GITHUB instalar
JAVA SDK
ANDROID STUDIO

----------Command------------

Gem install bundler
Gem install pretest
Gem install calabash-cucumber
Gem install calabash-android
Gem install capybara
Gem install cucumber
Gem install rspec
Gem install pry

Quando desistalar: gem uninstall

gem list

calabash-ios console calsmoke_cal

Query"*ID:'actions_bar_title'"

flash"*test:'chapterXXXXXXX'"

screenshot("/data/screenshots/imagem.png")


pretest create Nome_do_Projeto  --ios
				--android


bundle install

Emulator - AVD yaman

calabash-android resing android_sample.apk

calabash-android console android_sample.apk

start_test_server_in_background

tree (mostrar elementos)


touch "*text:'chapter10xxxxxxx'"
wait_fo_element_exists"*text:'chapter10xxxxxxx'"

reinstall apps

query ("*")

calabash-android run android_sample.apk

mkdir (Criar pasta)
open_(Nome do arquivo)

ADB devices (lista de aparelhos conectados)




---------------subir Git---------------
git status (modificações)
git add gitignore
git commit -m
git push
git checkout -b feature1      (Master*)
git clone (http://github....)

--------------Dependencias-------------
Ruby
Java sdk
AndroidStudio
Xcode
calabash cucumber
calabash android
cucumber

--------------scripts-----------------
cucumber
cucumber features/exemplo.feature
cucumber features/exemplo.feature:20
cucumber --tags @exemplo


------------actions IOS/ANDROID ------------

query("*id:'id_do_elemento'")
touch("*id:'id_do_elemento'")
keyboard_enter_text("texto esperado")
element_does_not_exist("*id:'id_do_elemento'")
element_exists("*id:'id_do_elemento'")
wait_for_elements_exists(["*id:'id_do_elemento'", "*id:'id_do_elemento_2'"])
wait_for_elements_exists("*id:'id_do_elemento'")
scroll("scrollView", :down)
uncheck("id_check")
screenshot("/data/screenshot.png")


Time OUT
wait_for_elements_exists("*id:'id_do_elemento'", timeout:7)





