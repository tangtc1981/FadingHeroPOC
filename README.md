# Fading Hero POC
Scrolling the ScrollView reduces the height of the hero pane, as well as fading out some of the hero pane content (White label text, image), and fading in some new content (Black label text). Once the hero is at it's minimum height, the scroll-pane continues to scroll under it.

Done in Xaml with two IValueConverters to manage opacity and hero height changes as bound to the ScrollY value of the ScrollView

Of course, some might like the Hero Image to not fade out in such a case, however what is plain from the Xaml is that this sort of thing is very easy to do / change / modify - and it's also a great illustration of reverse binding.

The following five images show the action of scrolling, notice that once the scroll-pane comes to it's top position, that the page within it continues to scroll upwards.

![Screenshot 1](https://github.com/Xamtastic/DiminishingMastheadPOC/blob/master/Screenshots/Screen%20Shot%201.png)

![Screenshot 2](https://github.com/Xamtastic/DiminishingMastheadPOC/blob/master/Screenshots/Screen%20Shot%202.png)

![Screenshot 3](https://github.com/Xamtastic/DiminishingMastheadPOC/blob/master/Screenshots/Screen%20Shot%203.png)

![Screenshot 4](https://github.com/Xamtastic/DiminishingMastheadPOC/blob/master/Screenshots/Screen%20Shot%204.png)

![Screenshot 4](https://github.com/Xamtastic/DiminishingMastheadPOC/blob/master/Screenshots/Screen%20Shot%205.png)
