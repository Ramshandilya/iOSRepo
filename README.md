![iOS Repo](../master/title.png)
####About
A list of awesome resources, libraries, frameworks for iOS developers.
***

##Contents
* [Architecture](#architecture)
* [Pure Swift](#pure-swift)
* [Foundation](#foundation)
	* [Color](#color)
	* [Date](#date)
	* [Operations](#operations)
	* [Timer](#timer)
* UI
	* [Animations](#animations)
	* [Activity Indicator](#activity-indicator)
	* [Alerts](#alerts)
	* [Button](#button)
	* [Cache](#cache)
	* [Calendar](#calendar)
	* [Camera & Gallery](#camera-and-gallery)
	* [Chat](#chat)
	* [CollectionView](#collectionview)
	* [Drawing](#drawing)
	* [Forms](#forms)
	* [Graphs](#graphs)
	* [Image](#image)
	* [Image Caching](#image-caching)
	* [Label](#label)
	* [Map](#map)
	* [Navigation](#navigation)
	* [Notification](#notification)
	* [Onboarding](#onboarding)
	* [Page Control](#page-control)
	* [PopOver](#popover)
	* [Pull-to-Refresh](#pull-to-refresh)
	* [Segment](#sement)
	* [Side Menu](#side-menu)
	* [Slider](#slider)
	* [Tab Bar](#tab-bar)
	* [TableView](#tableview)
	* [TextField](#textfield)
	* [Textview](#textview)
	* [Walkthrough](#walkthrough)
	* [Others](#others)
* [Networking](#networking)
	* [Network Layer](#network-layer)
	* [JSON Parsing](#json-parsing)
	* [Testing](#testing)
* [Data Layer](#data-Layer)
* [Image Processing](#image-processing)
* [Permissions](#permissions)
* [Security](#security)
* [Audio](#audio)
* [Video](#video)
* [Logging and Debug](#loggin-and-debug)
* [Analytics](#analytics)
* [Localization](#localization)
* [Misc](#misc) 
* [Version](#version)
* [Learn Swift](#learn-swift)
* [Coding Guide](#coding-guide)
* [AI](#ai)
* [Similar Compilations](#similar-compilations)

***
## Architecture
* [Design patterns in Swift](https://github.com/ochococo/Design-Patterns-In-Swift) 
* [The Principles of OOD](https://github.com/ochococo/OOD-Principles-In-Swift) - based on Uncle Bob articles.
* [ReSwift](https://github.com/ReSwift/ReSwift) - Unidirectional Data Flow in Swift - Inspired by Redux
* [Transporter](https://github.com/DenHeadless/Transporter) - Modern finite-state machine implemented in pure Swift
* [A composable pattern for pure state machines with effects](https://gist.github.com/andymatuschak/d5f0a8730ad601bcccae97e8398e25b2)
* [Square: Cleanse](https://github.com/square/Cleanse) - Lightweight Swift Dependency Injection Framework

## Pure Swift
### Algorithms
* [RayWenderlich: AlgorithmClub](https://github.com/raywenderlich/swift-algorithm-club) - Algorithms and data structures in Swift, with explanations!
* [SwiftStructures](https://github.com/waynewbishop/SwiftStructures) - Examples of commonly used data structures and algorithms in Swift.
* [Algorithm](https://github.com/CosmicMind/Algorithm)

### Error Handling
* [Result](https://github.com/antitypical/Result) - This is a Swift µframework providing `Result<Value, Error>`
* [DefaultErrorHandlerSwift](https://github.com/Ben-G/DefaultErrorHandlerSwift)

###Other 
* [Then](https://github.com/devxoul/Then) -  Super sweet syntactic sugar for Swift initializers.
* [FlatBuffersSwift](https://github.com/mzaks/FlatBuffersSwift) - an efficient cross platform serialization library
* [SwiftUtils](https://github.com/eonist/swift-utils)
* [Validated](https://github.com/Ben-G/Validated) - μ-Library for Somewhat Dependent Types

##Foundation
### Color
* [Chameleon](https://github.com/ViccAlexander/Chameleon) - Flat Color Framework for iOS
* [Hue](https://github.com/hyperoslo/Hue) - All-in-one coloring utility.
* [DynamicColor](https://github.com/yannickl/DynamicColor)

### Date
* [Date Extentions](https://github.com/erica/NSDate-Extensions) - Practical real-world dates
* [NSDate-TimeAgo](https://github.com/kevinlawler/NSDate-TimeAgo) - A "time ago", "time since", "relative date", or "fuzzy date" category for NSDate and iOS.
* [Timepiece](https://github.com/naoty/Timepiece) - Intuitive date handling.

### Operations
* [PSOperations](https://github.com/pluralsight/PSOperations) - A framework for advanced NSOperations usage https://developer.apple.com/videos/wwdc/2015/?id=226

### Timer
* [Swifty Timer](https://github.com/radex/SwiftyTimer) - Swifty API for NSTimer
* [EasyTimer](https://github.com/HighBay/EasyTimer) - for delaying code or repeating code.
* [Each](https://github.com/dalu93/Each) - Elegant ⏱ interface.


##UI
### Animations 
* [Fantastic iOS Animation](https://github.com/onmyway133/fantastic-ios-animation) - A collection of iOS animation repos
* [Stellar](https://github.com/AugustRush/Stellar) - A fantastic Physical animation library for swift
* [Advance](https://github.com/storehouse/Advance) - A powerful animation framework for iOS, tvOS, and OS X.
* [IFTTT: RazzleDazzle](https://github.com/IFTTT/RazzleDazzle)
* [Fluent](https://github.com/matthewcheok/Fluent) - Swift animation made easy.
* [Interpolate](https://github.com/marmelroy/Interpolate) - create interactive gesture-driven animations
* [Ramotion: CircleMenu](https://github.com/Ramotion/circle-menu)
* [BubbleTransition](https://github.com/andreamazz/BubbleTransition)
* [ElasticTransition](https://github.com/lkzhao/ElasticTransition)
* [AMWaveTransition](https://github.com/andreamazz/AMWaveTransition)
* [Ramotion: Preview Transition](PreviewTransition)
* [Ramotion: FoldingCell](https://github.com/Ramotion/folding-cell)
* [Yalantis: Star Wars](https://github.com/Yalantis/StarWars.iOS)
* [Jelly](https://github.com/SebastianBoldt/Jelly) - custom view controller transitions.
* [View2ViewTransition](https://github.com/naru-jpn/View2ViewTransition)

### Activity Indicator
* [NVActivityIndicatorView](https://github.com/ninjaprox/NVActivityIndicatorView)

### Alerts
* [PMAlertController](https://github.com/Codeido/PMAlertController)
* [XLActionController](https://github.com/xmartlabs/XLActionController)
* [TKSwarmAlert](https://github.com/entotsu/TKSwarmAlert)

### Button
* [LiquidFloatingActionButton](https://github.com/yoavlt/LiquidFloatingActionButton)
* [ActivityButton](https://github.com/justinHowlett/JHActivityButton)
* [Do Favorite Button](https://github.com/okmr-d/DOFavoriteButton)
* [KCFloatingActionButton](https://github.com/kciter/KCFloatingActionButton)
* [CRNetworkButton](https://github.com/Cleveroad/CRNetworkButton)

### Cache 
* [HanekeSwift](https://github.com/Haneke/HanekeSwift) - A lightweight generic cache for iOS written in Swift with extra love for images.

### Calendar
* [JTAppleCalendar](https://github.com/patchthecode/JTAppleCalendar)
* [Sapporo](https://github.com/nghialv/Sapporo)
* [CVCalendar](https://github.com/Mozharovsky/CVCalendar)
* [Calendar](https://github.com/jumartin/Calendar)

### Camera and Gallery
* [KYShutterButton](https://github.com/ykyouhei/KYShutterButton) - Custom button that is similar to the shutter button of the camera app
* [ALCameraViewController](https://github.com/AlexLittlejohn/ALCameraViewController) - A camera view controller with custom image picker and image cropping.
* [IFTTT: FastttCamera](https://github.com/IFTTT/FastttCamera) - Fasttt and easy camera framework for iOS with customizable filters.
* [Fusuma](https://github.com/ytakzk/Fusuma) - Instagram-like photo browser and a camera feature.
* [MHVideoPhotoGallery](https://github.com/mariohahn/MHVideoPhotoGallery) - A Photo and Video Gallery.
* [Yalantis: PixPic](https://github.com/Yalantis/PixPic) - A photo editing app.
* [PrismaSimpleImagePicker](https://github.com/Roylee-ML/PrismaSimpleImagePicker) - Prisma custom camera, image picker and picture editor
* [NohanaImagePicker](https://github.com/nohana/NohanaImagePicker)
 
### Chat
* [Chatto](https://github.com/badoo/Chatto)
* [MessageKit](https://github.com/MessageKit/MessageKit-iOS)
 
### CollectionView
* [YBSlantedCollectionView](https://github.com/yacir/YBSlantedCollectionViewLayout)
* [UPCarouselFlowLayout](https://github.com/ink-spot/UPCarouselFlowLayout) - A fancy carousel flow layout for UICollectionView on iOS.
* [Ramotion: ExpandingCollection](https://github.com/Ramotion/expanding-collection) - a card peek/pop controller
* [TGLParallaxCarousel](https://github.com/taglia3/TGLParallaxCarousel)
* [Koloda](https://github.com/Yalantis/Koloda) - Tinder like cards

### Drawing
* [NXDrawKit](https://github.com/Nicejinux/NXDrawKit) - A simple and easy but useful drawing kit for iPhone

### Forms
* [Eureka](https://github.com/xmartlabs/Eureka) - Elegant iOS form builder in Swift 2
* [Form Validator](https://github.com/ustwo/formvalidator-swift)

### Graphs
* [ScrollableGraphView](https://github.com/philackm/Scrollable-GraphView) - An adaptive scrollable graph view for iOS to visualise simple discrete datasets.
* [Charts](https://github.com/danielgindi/Charts)
* [Awesome iOS Charts](https://github.com/sxyx2008/awesome-ios-chart) - A curated list of awesome iOS chart libraries.

### Image
* [Translucid](https://github.com/Ekhoo/Translucid) - Set an Image as text background
* [XAnimatedImage](https://github.com/khaledmtaha/XAnimatedImage) - A performant animated GIF engine for iOS.
* [AspectFillFaceAware](https://github.com/BeauNouvelle/AspectFillFaceAware) - focus on faces within an image when using AspectFill.
* [FaceAware](https://github.com/BeauNouvelle/FaceAware)

### Image Caching
* [Nuke](https://github.com/kean/Nuke) - for loading, processing, caching and preheating images
* [Preheat](https://github.com/kean/Preheat) - Automates prefetching of content in UITableView and UICollectionView
* [Vulcan](https://github.com/jinSasaki/Vulcan)

### Label
* [CountdownLabel](https://github.com/suzuki-0000/CountdownLabel)
* [ActiveLabel](https://github.com/optonaut/ActiveLabel.swift) - UILabel drop-in replacement supporting Hashtags (#), Mentions (@) and URLs (http://) written in Swift
* [GlitchLabel](https://github.com/kciter/GlitchLabel) - G..lit...c...hing UILa..bel fo..r iO...S 📺

### Map
* [FBAnnotationClusteringSwift](https://github.com/ribl/FBAnnotationClusteringSwift)
 
### Navigation
* [Ramotion: Navigation Stack](https://github.com/Ramotion/navigation-stack)

### Notification
* [CWStatusBarNotification](https://github.com/cezarywojcik/CWStatusBarNotification) - Easily create text-based notifications that appear on the status bar.
* [JFMinimalNotifications](https://github.com/atljeremy/JFMinimalNotifications)
* [Whisper](https://github.com/hyperoslo/Whisper)
* [SwiftMessages](https://github.com/SwiftKickMobile/SwiftMessages)

### Onboarding
* [Ramotion: Paper Onboarding](https://github.com/Ramotion/paper-onboarding)
* [Onboard](https://github.com/mamaral/Onboard)

### Page Control
* [PageControls](https://github.com/popwarsweet/PageControls)

### PopOver
* [Popover](https://github.com/corin8823/Popover)

### Pull-to-refresh
* [Refresher](https://github.com/jcavar/refresher)
* [Yalantis: Rentals](https://github.com/Yalantis/Pull-to-Refresh.Rentals-iOS)
* [Yalantis: PullToRefresh](https://github.com/Yalantis/PullToRefresh)
* [DGElasticPullToRefresh](https://github.com/gontovnik/DGElasticPullToRefresh)

### Segment
* [Yalantis: Segmentio](https://github.com/Yalantis/Segmentio)

### Side Menu
* [SideMenuController](https://github.com/teodorpatras/SideMenuController) 

### Slider
* [HGCircularSlider](https://github.com/HamzaGhazouani/HGCircularSlider)
* [10Clock](https://github.com/joedaniels29/10Clock)

### SVG
* [Snowflake](https://github.com/onmyway133/Snowflake)
* [SwiftSVG](https://github.com/mchoe/SwiftSVG) - A single pass SVG parser with multiple interface options (String, NS/UIBezierPath, CAShapeLayer, and NS/UIView).
* [Macaw](https://github.com/exyte/Macaw)

### Tab Bar
* [Yalantis: Color Match Tabs](https://github.com/Yalantis/ColorMatchTabs)
* [Tab Drawer](https://github.com/winslowdibona/TabDrawer)
* [Yalantis: FoldingTabBar](https://github.com/Yalantis/FoldingTabBar.iOS)
* [Ramotion: Adaptive Tab Bar](https://github.com/Ramotion/adaptive-tab-bar)
* [Ramotion: Animated Tab bar](https://github.com/Ramotion/animated-tab-bar)

### TableView


### TextField
* [SkyFloatingLabelTextField](https://github.com/Skyscanner/SkyFloatingLabelTextField)
* [VENTokenField](https://github.com/venmo/VENTokenField) - Easy-to-use token field that is used in the Venmo app.
* [TFBubbleItUp](https://github.com/thefuntasty/TFBubbleItUp) -  for writing tags, contacts.
* [TextFieldEffects](https://github.com/raulriera/TextFieldEffects)

### TextView
* [NextGrowingTextView](https://github.com/muukii/NextGrowingTextView)
* [RSKGrowingTextView](https://github.com/ruslanskorb/RSKGrowingTextView)
* [EGFloatingTextField](https://github.com/enisgayretli/EGFloatingTextField) - Implementation of Google's "Floating labels" of Material design.
* [MMTextFieldEffects](https://github.com/mukyasa/MMTextFieldEffects)
* [UITextField-Shake](https://github.com/andreamazz/UITextField-Shake)
* [SlackTextViewController](https://github.com/slackhq/SlackTextViewController)

### Walkthrough
* [Gecco](https://github.com/yukiasai/Gecco) - Simply highlight items for your tutorial walkthrough, written in Swift
* [Instructions](https://github.com/ephread/Instructions)
* [BWWalkthrough](https://github.com/ariok/BWWalkthrough)
* [Presentation](https://github.com/hyperoslo/Presentation)

### Others
* [Facebook: AsyncDisplayKit](https://github.com/facebook/AsyncDisplayKit) - Smooth asynchronous user interfaces for iOS apps.
* [ISTimeline](https://github.com/instant-solutions/ISTimeline)
* [IKRouter](https://github.com/IanKeen/IKRouter) - URLScheme router than supports auto creation of UIViewControllers for associated url parameters to allow creation of navigation stacks
* [AAWindow](https://github.com/aaronabentheuer/AAWindow) - UIWindow subclass to enable behavior like adaptive round-corners & detecting when Control Center is opened.
* [StatefulViewController](https://github.com/aschuch/StatefulViewController) - Placeholder views based on content, loading, error or empty states.
* [StatusProvider](https://github.com/mariohahn/StatusProvider)
* [CreditCardForm](https://github.com/orazz/CreditCardForm-iOS)
* [EasyTipView](https://github.com/teodorpatras/EasyTipView)
* [SnapTimer](https://github.com/andresinaka/SnapTimer) - Snapchat's stories timer.
* [ComplimentaryGradientView](https://github.com/gkye/ComplimentaryGradientView) - Create complementary gradients generated from dominant and prominent colors in supplied image.

## Networking
### Network Layer
* [Networking](https://github.com/3lvis/Networking) - Simple HTTP Networking in Swift a NSURLSession wrapper with image caching support
* [URLNavigator](https://github.com/devxoul/URLNavigator) -  Elegant URL Routing for Swift
* [Moya](https://github.com/Moya/Moya) - Network abstraction layer written in Swift.

### JSON Parsing
* [Thoughtbot: Argo](https://github.com/thoughtbot/Argo) - Functional JSON parsing library for Swift 
* [Lyft: Mapper](https://github.com/lyft/mapper)
* [JSON Swift](https://github.com/owensd/json-swift)
* [Swifty JSON](https://github.com/SwiftyJSON/Alamofire-SwiftyJSON)

###Testing
* [Venmo: DVR](https://github.com/venmo/DVR) - Network testing for Swift.
* [Kakapo](https://github.com/devlucky/Kakapo) - Dynamically Mock server behaviors and responses in Swift.
* [Mockingjay](https://github.com/kylef/Mockingjay) - stub HTTP requests with ease.

###Other
* [Reachability](https://github.com/ashleymills/Reachability.swift)
* [Netfox](https://github.com/kasketis/netfox) - A lightweight, one line setup, iOS / OSX network debugging library.


## Data Layer
* [Pantry](https://github.com/nickoneill/Pantry) - The missing light persistence layer for Swift.
* [CoreStore](https://github.com/JohnEstropia/CoreStore) - Unleashing the real power of Core Data with the elegance and safety of Swift


## Image Processing
* [GPUImage2](https://github.com/BradLarson/GPUImage2) 
* [SwiftImageProcessing](https://github.com/skyfe79/SwiftImageProcessing) - Do pixel operations in swift.
* [Neural Style](https://github.com/jcjohnson/neural-style) - Prisma like Neural Networks.
* [Colornet](https://github.com/pavelgonchar/colornet) - Neural Network to colorize grayscale images
* [Filterpedia](https://github.com/FlexMonkey/Filterpedia) - Core Image Filter Explorer & Showcase
* [Toucan](https://github.com/gavinbunney/Toucan) - Fabulous Image Processing in Swift.

##Permissions
* [Arek](https://github.com/ennioma/arek) - wrapper over any kind of iOS permission.
* [PermissionScope](https://github.com/nickoneill/PermissionScope) - Intelligent iOS permissions UI and unified API
* [Permission](https://github.com/delba/Permission) - A unified API to ask for permissions on iOS.

##Security
* [Locksmith](https://github.com/matthewpalmer/Locksmith) - A powerful, protocol-oriented library for working with the keychain in Swift.
* [CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift) - Crypto related functions and helpers for Swift.
* [KeychainAccess](https://github.com/kishikawakatsumi/KeychainAccess)

## Audio
* [Chirp](https://github.com/trifl/Chirp) - The easiest way to prepare, play, and remove sounds in your Swift app.
* [novocaine](https://github.com/alexbw/novocaine) - Painless high-performance audio on iOS and Mac OS X.
* [AudioKit](https://github.com/audiokit/AudioKit)

## Video
* [Mobile Player](https://github.com/mobileplayer/mobileplayer-ios) - A powerful and completely customizable media player for iOS.

## Logging and Debug
* [XCGLogger](https://github.com/DaveWoodCom/XCGLogger)
* [CocoaLumberJack](https://github.com/CocoaLumberjack/CocoaLumberjack)
* [CleanroomLogger](https://github.com/emaloney/CleanroomLogger)
* [SwiftyBeaver](https://github.com/SwiftyBeaver/SwiftyBeaver)


## Analytics
* [HEAnalytics](https://github.com/HsoiEnterprises/HEAnalytics) - A simple Swift-based framework for iOS app analytics across analytics platforms.

## Localization
* [LocalizeSwift](https://github.com/marmelroy/Localize-Swift) - Swift 2.0 friendly localization and i18n with in-app language switching
* [Swifternalization](https://github.com/tomkowz/Swifternalization) - Localize iOS apps in a smarter way using JSON files.


## Misc
* [Swift Luhn](https://github.com/MaxKramer/SwiftLuhn) - Debit/Credit card validation port of the Luhn Algorithm
* [BarcodeScanner](https://github.com/hyperoslo/BarcodeScanner)
* [Pagination](https://github.com/MrAlek/PagedArray)
* [Jazzy](https://github.com/realm/jazzy)
* [iOS Bike Shedding](https://github.com/stanfy/ios-components-bikeshedding)
* [PromiseKit](https://github.com/mxcl/PromiseKit) - Powerful asynchronous programming.
* [FlagKit](https://github.com/madebybowtie/FlagKit) - Beautiful flag icons for usage in apps and on the web.
* [Device](https://github.com/Ekhoo/Device) - Light weight tool for detecting the current device and screen size written in swift.
* [Live](https://github.com/ltebean/Live) - Livestream demo
* [macOS Security & Privacy guide](https://github.com/drduh/macOS-Security-and-Privacy-Guide)
* [Matt Gallagher: CwlUtils](https://github.com/mattgallagher/CwlUtils)

##Version 
* [AppVersionMonitor](https://github.com/eure/AppVersionMonitor)
* [Siren](https://github.com/ArtSabintsev/Siren)


## Learn Swift
* [30 Days of Swift](https://github.com/allenwong/30DaysofSwift)
* [Swift-Radio-Pro](https://github.com/swiftcodex/Swift-Radio-Pro) - Professional Radio Station App, created w/ Swift 2.2
* [Swift a Day](https://github.com/lindadong/swift-a-day)


## Coding Guide
* [iOS Good Practices](https://github.com/futurice/ios-good-practices)
* [Swift Lint](https://github.com/realm/SwiftLint) - A tool to enforce Swift style and conventions.
* [Swift Style Guide](https://github.com/Ramshandilya/The-Swift-Style-Guide)

## AI
* [Neural Style](https://github.com/jcjohnson/neural-style) - Prisma like Neural Networks.
* [Colornet](https://github.com/pavelgonchar/colornet) - Neural Network to colorize grayscale images.
* [Deep Learning Kit](https://github.com/DeepLearningKit/DeepLearningKit) - Open Source Deep Learning Framework for Apple's iOS, OS X and tvOS.
* [Swift AI](https://github.com/collinhundley/Swift-AI) - An artificial intelligence and machine learning library in Swift.
* [BrainCore](https://github.com/aleph7/BrainCore) - The iOS and OS X neural network framework


## Similar Compilations
* [Awesome Awesomeness](https://github.com/bayandin/awesome-awesomeness)
* [Awesome iOS](https://github.com/vsouza/awesome-ios)
* [Awesome Swift](https://github.com/matteocrippa/awesome-swift)
* [Awesome Swift](https://github.com/Wolg/awesome-swift)
* [Awesome iOS UI](https://github.com/cjwirth/awesome-ios-ui)
* [tvOS](https://github.com/sanketfirodiya/tvOS)
* [Awesome Courses](https://github.com/prakhar1989/awesome-courses) - 📚 List of awesome university courses for learning Computer Science!
* [Awesome Datascience](https://github.com/okulbilisim/awesome-datascience) - 📝 An awesome Data Science repository to learn and apply for real world problems.
* [Awesome Computer Vision](https://github.com/jbhuang0604/awesome-computer-vision) - A curated list of awesome computer vision resources
* [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning)
