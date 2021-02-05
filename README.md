Please note, this project is now archived.

FontAwesomeDotNet
=================

A (very) simple wrapper for Font Awesome, facilitating use in .net desktop projects

[![Build status](https://ci.appveyor.com/api/projects/status/vw4qcnm6up3kwi5c?svg=true)](https://ci.appveyor.com/project/christophano/fontawesomedotnet)

Example usage (in WPF)

```xml
<UserControl xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
             xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
             xmlns:fa="clr-namespace:FontAwesome.Net;assembly=FontAwesome.Net">
  <UserControl.Resources>
    <FontFamily x:Key="FontAwesome">pack://application:,,,/FontAwesome.Net;component/Fonts/#FontAwesome</FontFamily>
  </UserControl.Resource>
  <StackPanel Orientation="Horizontal">
    <TextBlock FontFamily="{StaticResource FontAwesome}"
               Margin="5"
               FontSize="10"
               Text="{x:Static fa:FontAwesome.github}" />
    <TextBlock FontFamily="{StaticResource FontAwesome}"
               Margin="5"
               FontSize="14"
               Text="{x:Static fa:FontAwesome.github}" />
    <TextBlock FontFamily="{StaticResource FontAwesome}"
               Margin="5"
               FontSize="18"
               Text="{x:Static fa:FontAwesome.github}" />
    <TextBlock FontFamily="{StaticResource FontAwesome}"
               Margin="5"
               FontSize="24"
               Text="{x:Static fa:FontAwesome.github}" />
    <TextBlock FontFamily="{StaticResource FontAwesome}"
               Margin="5"
               FontSize="32"
               Text="{x:Static fa:FontAwesome.github}" />
    <TextBlock FontFamily="{StaticResource FontAwesome}"
               Margin="5"
               FontSize="40"
               Text="{x:Static fa:FontAwesome.github}" />
  </StackPanel>
</UserControl>
```
Results in:

![Result](https://cloud.githubusercontent.com/assets/3432137/4975115/4e5208f0-68cc-11e4-9ef9-34464b95707e.png)
