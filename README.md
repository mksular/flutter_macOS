macOS Flutter Kurulumu:
1- Flutter.dev / get started / install / macOS
2- Flutter SDK dosyalarını indir.
	/users/mksular/flutter/src
	klasörüne çıkar
3- Android Stüdyo Kur
	SDK dosyalarını
	/users/mksular/flutter/sdk
	klasörüne yükle
4- PATH işlemleri için
	/users/mksular/.zprofile
	dosyasını açıp
	
	export ANDROID_HOME=$ANDROID_SDK_ROOT
	xport ANDROID_SDK_ROOT=/Users/mksular/flutter/sdk
	export PATH=$PATH:/Users/mksular/flutter/src/flutter/bin

	Satırlarını ekliyoruz.
5- Visual Studio Code açıp
	flutter ve dart extensionlarını kuruyoruz.
6- flutter doctor komutunu çalıştırıyoruz.
	flutter doctor
	flutter doctor --android-licenses
	flutter config —-enable-web
7- Xcode kuralım.
	sudo xcode-select --switch /Applications/Xcode.app/Contents/Developer
	sudo xcodebuild -runFirstLaunch
	sudo xcodebuild -license
8- İlk Projemizi oluşturalım
	flutter create --org com.ideapark firstapp
9-CocoaPods kuralım.
	sudo gem install cocoapods
	pod setup
10-Uygulamayı Çalıştır.
