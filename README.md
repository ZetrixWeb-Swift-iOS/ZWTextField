# ZWTextField

![zwtextfield](https://cloud.githubusercontent.com/assets/24763760/21518631/e606704e-cd0d-11e6-8489-5bdcefcd5f7f.gif)

Welcoming all Xcoders!

As we all know, Apple released an awesome features like IBInspectable and IBDesignable with Xcode 6. These features are very useful to create application designs easily. It provides live support for creating application design with different property which we had to add earlier via code in property list. Now we can see live effect of all the property and can easily create our designs with live preview using storyboard only. Yes not even a single line of code required.

In this post, we are going to talk about how we can use this feature with UITextField. Here we are going to create different properties for UITextField which are not present in storyboard property list at design time. Here we have created one class file called ZWTextField, which has included some properties for textfield and that will be added in storyboard at design time.

Properties in ZWTextField:
borderColor: It is used to set color of border in UITextField. You can select color from colorpicker.
borderWidth: It is used to make border thick or thin. We can set itâ€™s value in pixels.
cornerRadius: It is used make rounded UITextField. We can define radius for corners.
placeHolderColor: It can be used to set placeholder text color.
rightImage: It is used to set image on right side for UITextField.
rightviewWidth: It is used to set width of right view.
leftImage: It is used to set image on left side for UITextField.
leftviewWidth: It is used to set width of left view.
bottomLineWidth: It is used to set only bottom border.when we want only bottom border this property is very useful.
bottomLineColor: It is used to set only bottom border color.you can select color from color picker.
paddingLeft: It is used to set padding(blank space) from left side. We can set it in pixels.
paddingRight: It is used to set padding(blank space) from right side. We can set it in pixels.
topBorderColor: We can set color for top border using color picker.
topBorderHeight: We can set height for top border in pixels.
bottomBorderColor: We can set color for bottom border using color picker.
bottomBorderHeight: We can set height for bottom border in pixels.
leftBorderColor: We can set color for left border using color picker.
leftBorderHeight: We can set height for left border in pixels.
rightBorderColor: We can set color for right border using color picker.
rightBorderHeight: We can set right for bottom border in pixels.
maxLength: We can set maximum character limit for UITextField.
