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

POJO
	plain old java object
	quit the complex of java class
	old
		not use java framework
		more simple posible
	oriented object programaing
	simple class abstract in object and this object transform on POJOs
	POJO class without funcionality the most simple posible

Android es MVC for default
	Model
		Java lengauje
	Controller
		Java lengauje
	View
		Interface in xml 
		layout(all views on andoird call layouts)

	Controller
		all this instructors go define on the controlleres
		of this form controller all elemnets of the view 
	Model
		Business model 
		POJOs are the modle of the system
		relational with DB

Controller
	call the model (push data in the model)
	setContentView(R.layour.activiry_main)
		controller this view
	model
		Alumno alumno = new Alumno();


layout
	not subfolders


SnackBar
	bar on bottom of the scrreen


manipulate xml vs Graphic Editor
	xml 
		esquematizacion lenguaje

views
	is a object that you sue to draw something in the screen whitn th user interactive
	is a object
view group
	each view group can more view group

	Linear Layout
		is view group
		order the sons in only directino horizontal or vertical
	Relative Layout
		is a view group
		sons position is relative 
			view
			parent
	Not use
		absoutle layout
		table layoutr
	More layouts
		ListView
			scroll
		GridView
			sutitute the table layout

Android orientation 
	verticarl
	horizontal

Properties
	android:layout_width
		width
	android:layout_height
		height
	android:text
		text of the view
	android:id
		id view
	android:layout_below
		position below
	android:layout_centerInParent
		center according to the parent
	android:src 
		src of image
	@dimen 
		usa dimesion
	EditText
		inputType
Basics Widgets
	TextView
		Text tag is like a label
	EditText
		Permit diferent kind of text
			email
			numeric
			password
Button 
	Porcion fo text or image or both that help us to stablisher comicacion with accinns when the user touch it
	Image Button
		android:src 
			src of the image
				drawable
	Actions
		onClick
			asign a disponible method
		setOnClickListener

wrap_content
	envolver->wrap
		the space the elmento into 
android:layoutgranvity="center_horizontal"
android:hint
	placeholder
android:id="@+id/nombre_id"

Toast
	Is a menssage that it notificate retroalimentation

How manipulate view of java code
	//not need new becaus you create another view 
	//user R for the references of the resources
	EditText edtNombre = findViewById(R.id.nombre); //choise a elemento by id this return a view for this you need a cast
	EditText edtNombre = (EditText) findViewById(R.id.nombre);
	String nombre = edtNombre.getText().toString();

android:onClick="enviar datos"

public void enviarDAtos(View view){
	EditText edtNombre = (EditText) findViewById(R.id.nombre);
	String nombre = edtNOmbre.getTExt().toString();

	Toast.makeText(getBaseContext(), "Felicidades tu nobmre es. " + nombre, Toast.LENGTH_LONG).show();

Material Design 
	Is a integral guide for the visual design, of movements and interaction in distins platforms and dispositives
	new theme
	new widgets
	new libs for animations
		transitions 
		animations
Material Design Theme
	Dark
	@android:style/Theme.Material.Light
	@android:style/Theme.Material.Light.DarkActionBar

Design lib
	Theme.AppCompat
		Compability of old versions
	styles.xml
		configurate the styles of the app
	Three principal colors
		colorPrimary
			general elements all time on the app
		colorPrimaryDark
			general use on android lollypop

Configurate Material Design 

}	

res
	values
		Styles.xml
			noActionBar //quit the action bar
Select three colors for pallette or material design
	500 primary colors avalible
	500< primary dark colors
	A letter acentuation color
		colors.xml
			you put the 3 colors of material design for you design 
@ reference to tag
/ name 


materialpalette.com
	you can select two colors and this generate all pallette for use in your proyect

Widgets Material Design
	Toolbar
		new tag integrate
	Textinputlayout
	TextInputEditText
		define a text type of password,email
	Raised Button
		new style for the button tag
	Floating Action Button
		new button reduce menus
	CardView
		best ux user expirence
	RecyclerView
		sustitue ListView

Coordinator Layout
	Is a parent layout

Activity
	Is a component of a app that it provided of a screen for the user interactive whit it

	Archivo java
		java class extends activity
		java class take the layout and show in the screen
		all activity should be declared on AndroidManifest.xml
Application tag
	icon who use the app
	label name of application menu
	theme style
	activity tag
		.LoginActivity
			. is becaouse you nedd reference all package
	intent-filter(one time no more)
		define a place for screen
	Action
		dfine when open the app the first scrren (will login screen)

Activity
	is each screen of the app
	lifecycle
		Created
			When the activity is created
			receive
				bundle: save the state of the previus activity
				super// reference to parent classs

		Started
			render all elements of the acitvity

		Resumed
			when the ativity finished to rendered
		Paused
			Partially visible
			when you call another activity
		Stop
			execute when i press the home boton and the activity will be stopped
		Destroy
			when we press the back buton 
Coordinatro layout
	namespace
		all words like android tools you can acces to them 
			this methop pertenice to activity
		context
			file whoh contoller this acti

weigthSum
	the weigth of the parent 1
layout_weigth
	the weigth of the sons 0.6

Andorid Stdio
	prefereces (the key)
		plugins
			androidDrawableImporter
batchDrawable import(diferente densities of image)
	hit (placeholder )
		you need define all string on string files string.xml
internazinatiion
	string.xml
		create different strings files for the different lenguajes
fro antoher lengujajes
	you need to create a new values-en folder
		you can different views about you code 
			projecr view 
			development view
alt+enter
	create a strig or resources that you want on the app

live 
	stripe 
		with sripe is more easy to open a account 
button rise
	button state
		normal
			colorButtonNormal
you can creta syles for the elemnts fo the app

sp mesure unit

android:fillviewport : true
	element use all space 

Toolabar
	manager on diferrent file is recommedede
Strings of Java code
	getResources().getString(R.string.toolbar_tittle_creteaccount)

Intents
	When you need join differenct activities on the app
	two forms
		link actvity 1 with activity 2
	Implicits
		unifiquete 

Activity A
	startActivity()
		inteetn call Android system
	onCreate
activity B

Intent intent = new INtent(this, Create AccouunActivity.class);
startActivity(intent);
	Botón back
		Destroy the activity
	Botón Up
		jerarquy into the app
		bookList
			Book1
			Book2
add parent to son activity
	parentActivityName".LoginAcrivity"

CardView
	Is a ViewGroup
	Permit show information into the cards
	can modifi the borders and add shadows if we want
	varius views componend the card view

	Tag CardView suport library
	Layout into the CardView
	ImageView and 2 Image Butotn items
	Is neccesary to add the library to support gradle
RecyclerView
	More efficent that ListView
Floating Actin Button
	Design Library
	is a tag

CardView
	separeted file work the card views
	is a external library
	cardCornerRadius
		borders rendondeados
	cardElevation
Imageview
	scaleType
		centerCrop crop overflow 		
icons8.com
	icons webpage

Selector
	state_checked
		false
		true
Fragments
	introduce for the tablets
	FragmentA+FragemntB one view (tablets)
	FragmentA|FragmentB separeted view(smartphone)
	Fragment live on the Activity
	Switch fragment into the activity

Fragement Manager
	support library
	Transaccion
		all actins you can realize in the fragment
	Commits
		if you did a transaccion is very impootant you do a commit 
Fragment
	Class
	file xml
	apper to a activity
BottomBar
	not exit
	is a library

alignParentBotton

bb_inActiveTabColor
	when a tab of the bottombar is inActive

www.romannurik.github.io
	generate of icons

default tab
setDefaultTab()

Listener 
	when you touch someone of the tags

RecyclerView
	not use listView
	just loading the items who can watch on the screen
Structure
	RecyclerView
		LayoutManager
			List(LinearLaoyutManager)
			Grid(GridLayoutManager)
			Escalonable()
	Adapter
		Design patron
		Class Adapter
			class ViewHolder
	Dataset
		POJO
RecyclerView
	RecyclerView.ViewHolder //parent class

	Adapter
		Array list for recycle the views of the cards
		Collections of objects

LayoutInflater.from(parent.getContext()).infalte(resource,parent, false);
show xml like a view 

onBindViewHolder
	recorrer the view 

Picasso  android
	context
	image 
	element
		take image from internet

permission 
	private user resources you need permission you declared thiese on AndroidManifest.xml
widget 
	nestedScrollView
		use when the element not overflow the screen 
		use a layout

layout_anchor
	you put a element over another element

CoordinatorLayout
	Super FrameLayout
	help to especify interaccins in the son views
	flot views

layout inflation
	convertin xml appearace dfinition into View objects in code is called infaltion
	very time consuming....
		take an xml view, create its java object, set values for all attributes, and reursivley repeat for all its child nodes
		Use the getSystemSErvice() or getLayoutInflater8) to create an oject to Layout INflater 
		Only precompiled xml files by the aapt can be inflated during runtime for performance
AppBarLayout
	Is a lineraLayoutVertical
	Permit mangaer caracteristics of Material desing
CollapsingToolbarLayout
	Is a wrapper for toolbar implement collpsable efect
	you need son of the back element

What is the difference between:

px
dip
dp
sp
on Android?

in
Inches - based on the physical size of the screen.
1 Inch = 2.54 centimeters
mm
Millimeters - based on the physical size of the screen.
pt
Points - 1/72 of an inch based on the physical size of the screen.
dp or dip
Density-independent Pixels - an abstract unit that is based on the physical density of the screen. These units are relative to a 160 dpi screen, so one dp is one pixel on a 160 dpi screen. The ratio of dp-to-pixel will change with the screen density, but not necessarily in direct proportion. Note: The compiler accepts both "dip" and "dp", though "dp" is more consistent with "sp".
sp
Scale-independent Pixels - this is like the dp unit, but it is also scaled by the user's font size preference. It is recommend you use this unit when specifying font sizes, so they will be adjusted for both the screen density and user's preference.
From Understanding Density Independence In Android:

+----------------+----------------+---------------+-------------------------------+
| Density Bucket | Screen Density | Physical Size | Pixel Size                    | 
+----------------+----------------+---------------+-------------------------------+
| ldpi           | 120 dpi        | 0.5 x 0.5 in  | 0.5 in * 120 dpi = 60x60 px   | 
+----------------+----------------+---------------+-------------------------------+
| mdpi           | 160 dpi        | 0.5 x 0.5 in  | 0.5 in * 160 dpi = 80x80 px   | 
+----------------+----------------+---------------+-------------------------------+
| hdpi           | 240 dpi        | 0.5 x 0.5 in  | 0.5 in * 240 dpi = 120x120 px | 
+----------------+----------------+---------------+-------------------------------+
| xhdpi          | 320 dpi        | 0.5 x 0.5 in  | 0.5 in * 320 dpi = 160x160 px | 
+----------------+----------------+---------------+-------------------------------+
| xxhdpi         | 480 dpi        | 0.5 x 0.5 in  | 0.5 in * 480 dpi = 240x240 px | 
+----------------+----------------+---------------+-------------------------------+
| xxxhdpi        | 640 dpi        | 0.5 x 0.5 in  | 0.5 in * 640 dpi = 320x320 px | 
+----------------+----------------+---------------+-------------------------------+


+---------+-------------+---------------+-------------+--------------------+
| Unit    | Description | Units Per     | Density     | Same Physical Size | 
|         |             | Physical Inch | Independent | On Every Screen    | 
+---------+-------------+---------------+-------------+--------------------+
| px      | Pixels      | Varies        | No          | No                 | 
+---------+-------------+---------------+-------------+--------------------+
| in      | Inches      | 1             | Yes         | Yes                | 
+---------+-------------+---------------+-------------+--------------------+
| mm      | Millimeters | 25.4          | Yes         | Yes                | 
+---------+-------------+---------------+-------------+--------------------+
| pt      | Points      | 72            | Yes         | Yes                | 
+---------+-------------+---------------+-------------+--------------------+
| dp      | Density     | ~160          | Yes         | No                 | 
|         | Independent |               |             |                    | 
|         | Pixels      |               |             |                    | 
+---------+-------------+---------------+-------------+--------------------+
| sp      | Scale       | ~160          | Yes         | No                 | 
|         | Independent |               |             |                    | 
|         | Pixels      |               |             |                    | 
+---------+-------------+-------


scrollFlags
	collpase efect to the sons


Questions
	What is infation?
	different type of messure on android?
	functino of adpater?
View
	ViewGroup
		AdapterVire
			Listview
			Gridview
			Spinerr
			GAllary

ArrayAdpater
SimpleCursoAdapter
BaseAdapter

anchor 
	who go colgado

Depended comportamiento
	
Simple view behavior
	dependsOn
	depende type
		y eje
	dependTargetY
		what is the limit for the y eje
	targetX 
		like a margin when the image finish the transition
	targetWidth
		what si the final whith of the image

Transition Android
	exitTransition() Activity 1
	starTransiiton() Acivity 2
		Fade
		Slide Explode
	transitionName
		is ipmortant it's be complete word
	you need do a validation for the transition
		if(Build.VERISON.SDK_INT >= Build.VERSION_CODES.LOLLIPOP){
			Explode explode = new Explode();
			explode.setDuration();
			activity.getWindow().setExitTransiiton(explode);
			activity.startActivity(intent, AcitvityOptionsCompat.makeSceneTransitionanimation(activity, view, activity.getStraing(R.string.transitionanem_picture)).toBundle);
	}
	it's work on version mayor to llollipop
	if(Build.VERSION.SDK_INT >= Build.VERSION_CODES.LOLLIPOP);

styles.xml(v21)

version control
	vcs
		unable to the vcs 
	vcs
		impor tinto version control
		select github