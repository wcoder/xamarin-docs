---
title: "XAML Standard (Preview) Controls"
description: "How to get started exploring the XAML Standard Preview in Xamarin.Forms"
ms.topic: article
ms.prod: xamarin
ms.assetid: 287E6631-D1C5-46C5-8905-AB53D34E365D
ms.technology: xamarin-forms
author: charlespetzold
ms.author: chape
ms.date: 11/15/2017
---

# XAML Standard (Preview) Controls

![Preview](~/media/shared/preview.png)

This page lists the XAML Standard controls available in the
Preview, alongside their equivalent Xamarin.Forms control.

There is also a list of controls that have new property and
enumeration names in XAML Standard.

## Controls

|Xamarin.Forms|XAML Standard|
|--- |--- |
|Frame|Border|
|Picker|ComboBox|
|ActivityIndicator|ProgressRing|
|StackLayout|StackPanel|
|Label|TextBlock|
|Entry|TextBox|
|Switch|ToggleSwitch|
|ContentView|UserControl|


## Properties and Enumerations

|Xamarin.FormsControls with updated properties|Xamarin.FormsProperty or Enum|XAML StandardEquivalent|
|--- |--- |--- |
|Button, Entry, Label, DatePicker, Editor, SearchBar, TimePicker|TextColor|Foreground|
|VisualElement|BackgroundColor|Background *|
|Picker, Button|BorderColor, OutlineColor|BorderBrush|
|Button|BorderWidth|BorderThickness|
|ProgressBar|Progress|Value|
|Button, Entry, Label, Editor, SearchBar, Span, Font|FontAttributesBold, Italic, None|FontStyleItalic, Normal|
|Button, Entry, Label, Editor, SearchBar, Span, Font|FontAttributes|FontWeights *Bold, Normal|
|InputView|KeyboardDefault, Url, Number, Telephone, Text, Chat, Email|InputScopeNameValue *Default, Url, Number, TelephoneNumber, Text, Chat, EmailNameOrAddress|
|StackPanel|StackOrientation|Orientation *|

> [!IMPORTANT]
> Items marked with * are incomplete in the current preview

## Related Links

- [Preview NuGet](https://aka.ms/xf-xamlstandard-nuget)
