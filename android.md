rx-java
adpaters

images
	use official documentation
	use a plugin include on android studio
		image density
			different resolution take a original image
			not care about dispositive proportion is the same in all screnn
	open jdk
	oracle jdk


definition
	is the operative system use in billons of smartphone and tablets
candy for version of android
	new version is something new on own dispositive
android
	start 2003
		AndryRubin
		RichMiner
	2005 
	2008
		android 1.0 (apple pie)
		android 1.1 (banana bread) bugs on 1.0
		android 1.5 (cupcake) first version with sdk
			touch keyboard
			bluethoot
		android 1.6 (donut)
			search box
			android market
			support for varius screen tamanño
				(no pixels)
		android 2.0 (Eclair)
			google map navigation
			start screen 
			voice search
		android 2.2 (Eclair)
			best voice search
			portatil wifi
			performace 
				dalvik JIT(Just in Time)
					all app is compiling each time own open apps
					javacscirpt engine V8
		android 2.3 (gingerbread)
			create videogames
			NFC sensor (sensor de proximidad)
			batterie manager
		android 3.0 (honeycomb)
			design for tablets
			touch bottons
			multitask bottons
			fragment
			asyntask
		android 4.0 (ice cream sandwich)
			start screen (PERSONALIZADO)
			folder for app (PERSONALIZADO)
		android 4.1(jelly bean)
			google now
				personal assitenet
			notificaction down
			multiple users
		android 4.4(kit kat)
			Ok google
			smartphone learn your preferences
				contacts
				calls
				google mas
					frecuenqly places
		android 5.0(lollipop)
			material design
			multiples screen
			notifiacation on block screen
		android 6.0(Marshmallow)
			manager allows
			save batteri
				no compile save on register and app open much fast
		android  7.0(Nougat)
			lenguaje add:
				emojis
				more lenguajes
			Personalize Notifications
			Security

Actual State of android
	
Requirements for development system
	widnows
		7,8,10
	mac
		mac os x (10,8.5) or next version 10,11,4(The Capitan)
	linux
		GNOME o KDE 
			recomendation(ubuntu)

	4gb minimun
	resolution minimun 1280 x 800

	procesdor intel

Software
Java
	1.7
Android Studio
SDK Android
	Software development kit android
	alal version of android
	emulate virtual dispositives

Arquitecutre of Android app

	Andoird Proyect
		libraries
		resoruces and views files
			views
				grapick intreaces
				xml format
		source 
			java engine 
		Android manifest
			all app with android os

Ejecutable APK
	apk is a kind of package
	application package

App code
	bytecode
		classes.dex (more optimization por smarhphone)
	native code
		libs/<arch>/*.so
Resources
	res/
	resources.arsc

	use la minimn of libs 
Misc
	assets/
	META-INF/
	AndroidManifest.xml

Android Studio
	Basado en IntelliJ IDEA
		Instant run
			play and stop buttom
		Smart code editor
			more suggestion when yo are codign
		Design for teams
		Development for all android dispositive
Android sdk manager
	1.- configure
		sdkmanager
		recomendable 
			Android 4.0 (install all since this version)
			sdk platform(all lib that developed for android)
			arm (virtual image of this version of android)
			intel x86 (different arquitectru with intel processor)
			google APIs (service like google maps (google propietari) suppor for google services)

package naem 
	com.hanmilton.holamundo
		name of your app on app store
	Company Domain
		web site (how your compnay is identify for others)
Projecto locaton
	where you put your app
	workspace
Minimun SDK
	minimun version compatibility for your app
Add an acrivity to Mobile
	Is like a initial scrren 

Activivy
	Java File
	Layout
		xml file
Gradle
	dependency manager
	generate all resoruces a own proyect in memory
	construct own proyect

	Source code
		java folder
	res
		resources 
			images 
			text
			videos 
			drawable
				all images
			layourt
				all interfaces (xml files)
			menu
				all menus (xml files)
			mipmap
				all icons of app
			values
				resources
					colors
					dimeens
						dimension 
					string
						all text of the app
					styles

Manifest
	AndroidManifesto.xml
		all configuration with respect to the operative system

create emulator
	avd manager
		android virtual device manager
skin
	skin of the cellphone
system image
	configuration of the software
armavi 
	is a procesador
	



