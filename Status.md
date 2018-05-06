# Status

## To-Do
* Accessibility
* List (Lot of work)
* NativeViewWrapper
* NavigationMenu

## Pages

### ContentPage

A [ContentPage](https://developer.xamarin.com/api/type/Xamarin.Forms.ContentPage/) is a Page displaying a single View, often a container like a StackLayout or ScrollView.

Property | Status
------ | ------
BackgroundColor   | Done  
Appearing   | Done  
Disappearing   | Done  

### MasterDetailPage

A [Page](https://developer.xamarin.com/api/type/Xamarin.Forms.MasterDetailPage/) that manages two panes of information: A master page that presents data at a high level, and a detail page that displays low-level details about information in the master.

Property | Status
------ | ------
Detail   | Done  
IsGestureEnabled   | Pending  
IsPresented   | Done  
Master   | Done  
MasterBehavior   | Pending  
ShouldShowToolBarButton   | Pending  
IsPresentedChanged   | Done  

### NavigationPage

A [Page](https://developer.xamarin.com/api/type/Xamarin.Forms.NavigationPage/) that manages the navigation and user-experience of a stack of other pages.

Property | Status
------ | ------
Animate   | Done  
Add   | Done  
Remove   | Done  

### TabbedPage

[Displays](https://developer.xamarin.com/api/type/Xamarin.Forms.TabbedPage/) an array of tabs across the top of the screen, each of which loads content onto the screen.

Property | Status
------ | ------
BarBackgroundColor   | Done  
BarTextColor   | Done  
ItemsSource   | Done  
ItemTemplate   | Done  
SelectedItem   | Done  
GetIndex   | Done  
GetPageByIndex   | Done  
SetIndex   | Done  
Appearing   | Done  
Disappearing   | Done  
CurrentPageChanged   | Done  
PagesChanged   | Done 

### CarouselPage

The Xamarin.Forms [CarouselPage](https://developer.xamarin.com/guides/xamarin-forms/application-fundamentals/navigation/carousel-page/) is a page that users can swipe from side to side to navigate through pages of content, like a gallery. 

Property | Status
------ | ------
ItemsSource   | Done  
ItemTemplate   | Done  
CurrentPage   | Done  
Children   | Done  
BackgroundImage   | Done  
Icon   | Pending  
IsBusy   | Done  
Padding   | Done  
Tittle   | Done  
ToolbarItems   | Done  
CurrentPageChanged   | Done  
PagesChanged   | Done  
LayoutChanged   | Done  
Appearing   | Done  
Disappearing   | Done  

## Views

### ActivityIndicator

The [ActivityIndicator](https://developer.xamarin.com/api/type/Xamarin.Forms.ActivityIndicator/) control gives a visual clue to the user that something is happening, without information about its progress.

Property | Status
------ | ------
BackgroundColor   | Pending  
IsRunning   | Done  
Color   | Done  

### ActionSheets

The UIActionSheet is a common UI element in iOS. The Xamarin.Forms [DisplayActionSheet](https://developer.xamarin.com/guides/xamarin-forms/application-fundamentals/navigation/pop-ups/) method lets you include this control in cross-platforms apps, rendering native alternatives.

Property | Status
------ | ------
Title   | Done  
Cancel   | Done  
Extras   | Done  
Destruction   | Done  

### BoxView

[BoxView](https://developer.xamarin.com/api/type/Xamarin.Forms.BoxView/) is a useful stand-in for images or custom elements when doing initial prototyping. 

Property | Status
------ | ------
BackgroundColor   | Done  
Color   | Done  

### Button

A [button](https://developer.xamarin.com/api/type/Xamarin.Forms.Button/) View that reacts to touch events.

Property | Status
------ | ------
BackgroundColor   | Done  
IsEnabled   | Done  
Command   | Done  
CommandParameter   | Done  
ContentLayout   | Done  
Text   | Done  
TextColor   | Done  
Font   | Done  
FontFamily   | Done  
FontAttributes   | Done  
BorderWidth   | Done  
BorderColor   | Done  
BorderRadius   | Pending  
Image   | Done  
Clicked   | Done  
Pressed   | Done  
Released   | Done  

### DatePicker

The visual representation of a [DatePicker](https://developer.xamarin.com/api/type/Xamarin.Forms.DatePicker/) is very similar to the one of Entry, except that a special control for picking a date appears in place of a keyboard.

Property | Status
------ | ------
BackgroundColor   | Done  
Format   | Pending 
Date   | Done  
MinimumDate   | Done  
MaximumDate   | Done  
TextColor   | Done  
DateSelected   | Done  

### Editor

The [Editor](https://developer.xamarin.com/guides/xamarin-forms/user-interface/text/editor/) control is used to accept multi-line input.

Property | Status
------ | ------
BackgroundColor   | Done  
IsEnabled   | Done  
Text   | Done  
FontFamily   | Done  
FontSize   | Done  
FontAttributes   | Done  
TextColor   | Done  
TextChanged   | Done  

### Entry

[Entry](https://developer.xamarin.com/api/type/Xamarin.Forms.Entry/) is a single line text entry. It is best used for collecting small discrete pieces of information, like usernames and passwords.

Property | Status
------ | ------
BackgroundColor   | Done  
IsEnabled   | Done  
Placeholder   | Done  
PlaceholderColor   | Done  
Text   | Done  
TextColor   | Done  
FontFamily   | Done  
FontSize   | Done  
FontAttributes   | Done  
TextColor   | Done  
TextChanged   | Done  
Completed   | Done  

### Frame

[Frame](https://developer.xamarin.com/api/type/Xamarin.Forms.Frame/) is an element containing a single child, with some framing options.

Property | Status
------ | ------
BackgroundColor   | Done  
outlineColor   | Done  
HasShadow   | Done  

### Label

A [Label](https://developer.xamarin.com/api/type/Xamarin.Forms.Label/) is used to display single-line text elements as well as multi-line blocks of text.

Property | Status
------ | ------
BackgroundColor   | Done  
IsEnabled   | Done  
FormattedText   | Done
HorizontalTextAlignment   | Done  
LineBreakMode   | Done  
Text   | Done  
TextColor   | Done  
VerticalTextAlignment   | Done  
FontAttributes   | Done  
FontFamily   | Done  
FontSize   | Done  
XAlign   | Done  
YAlign   | Done 

### OpenGLView

A [View](https://developer.xamarin.com/api/type/Xamarin.Forms.OpenGLView/) that displays OpenGL content.

Property | Status
------ | ------
HasRenderLoop   | Done  

### Picker

A [View](https://developer.xamarin.com/api/type/Xamarin.Forms.Picker/) control for picking an element in a list.

Property | Status
------ | ------
Title   | Pending  
SelectedIndex   | Done  
ItemsSource   | Done  
SelectedItem   | Done  
Items   | Done  
itemDisplayBinding   | Done  
SelectedIndexChanged   | Done  

### Progress

A [View](https://developer.xamarin.com/api/type/Xamarin.Forms.ProgressBar/) control that displays progress.

Property | Status
------ | ------
BackgroundColor   | Done  
Progress   | Done  
ProgressTo   | Done  
ProgressColor | Done 

### ScrollView

An [element](https://developer.xamarin.com/api/type/Xamarin.Forms.ScrollView/) capable of scrolling if its Content requires.

Property | Status
------ | ------
BackgroundColor   | Done  
Orientation   | Done  
ScrollX   | Done  
ScrollY   | Done  
Content   | Done  
ContentSize   | Done  
ScrollToAsync   | Done 
Scrolled   | Done  

### SearchBar

A [View](https://developer.xamarin.com/api/type/Xamarin.Forms.SearchBar/) control that provides a search box.

Property | Status
------ | ------
BackgroundColor   | Done  
SearchCommand   | Done  
SearchCommandParameter   | Done  
CancelButtonColor   | Pending  
Placeholder   | Pending  
FontFamily   | Done  
FontSize   | Done  
FontAtttributes   | Done  
HorizontalTextAlignment   | Done  
TextColor   | Done  
PlaceholderColor   | Pending  
FontFamily   | Done  
SearchButtonPressed   | Done  
TextChanged   | Done  

### Slider

A [View](https://developer.xamarin.com/api/type/Xamarin.Forms.Slider/) control that inputs a linear value.

Property | Status
------ | ------
BackgroundColor   | Done  
Minimum   | Done  
Maximum   | Done  
Value   | Done  
ValueChanged   | Done  

### Stepper

A [View](https://developer.xamarin.com/api/type/Xamarin.Forms.Stepper/) control that inputs a discrete value, constrained to a range.

Property | Status
------ | ------
BackgroundColor   | Done  
Minimum   | Done  
Maximum   | Done  
Value   | Done  
Increment   | Done  
ValueChanged   | Done  

### Switch

A [View](https://developer.xamarin.com/api/type/Xamarin.Forms.Switch/) control that provides a toggled value.

Property | Status
------ | ------
BackgroundColor   | Done  
IsToggled   | Done  
Toggled   | Done  

### TimePicker

A [View](https://developer.xamarin.com/api/type/Xamarin.Forms.TimePicker/) control that provides time picking.

Property | Status
------ | ------
BackgroundColor   | Done  
Format   | Done  
TextColor   | Done  
Time   | Done  

### TableView

A [View](https://developer.xamarin.com/api/type/Xamarin.Forms.TableView/) that holds rows of Cell elements.

Property | Status
------ | ------
BackgroundColor   | Done  
HasUnevenRows   | Done  
TableIntent   | Done  
RowHeight   | Done  
Root   | Done  
ContextActions   | Done  

### WebView

A [View](https://developer.xamarin.com/api/type/Xamarin.Forms.WebView/) that presents HTML content.

Property | Status
------ | ------
CanGoBack   | Done  
CamGoForward   | Done  
Source   | Done  
Eval   | Done  
GoBack   | Done  
GoForward   | Done  
Navigated   | Done  
Navigating   | Done  

### VisualElement

Property | Status
------ | ------
BackgroundColor   | Done  
AnchorX   | Done  
AnchorY   | Done  
IsEnabled   | Done  
IsFocused   | Done  
IsVisible   | Done
Opacity   | Done  
RotationX   | Pending  
RotationY   | Pending  
Scale   | Done  
TranslationX   | Done  
TranslationY   | Done
