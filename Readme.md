<!-- default file list -->
*Files to look at*:

* **[MainPage.xaml](./CS/MapPushpinTemplate/MainPage.xaml) (VB: [MainPage.xaml](./VB/MapPushpinTemplate/MainPage.xaml))**
* [MainPage.xaml.cs](./CS/MapPushpinTemplate/MainPage.xaml.cs) (VB: [MainPage.xaml](./VB/MapPushpinTemplate/MainPage.xaml))
<!-- default file list end -->
# How to provide a custom pushpin for a map


<p>This example demonstrates  how to implement a custom pushpin using its template. </p><br />
<p>To accomplish this,  it is necessary to create a <strong>System.Windows.DataTemplate</strong> that contains the <strong>StackPanel</strong> with a custom pushpin image and<strong> TextBlock</strong> (specifies the pushpin title). </p><p>Then, add this data template to a window's resource and apply it to a map pushpin via the <a href="http://documentation.devexpress.com/#Silverlight/DevExpressXpfMapMapPushpin_Templatetopic"><u>MapPushpin.Template</u></a> property.</p><br />


<br/>


