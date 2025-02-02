+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true # Activate this widget? true/false
weight = 20  # Order that this section will appear.

title = ""
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  #gradient_start = "DarkGreen"
  #gradient_end = "ForestGreen"
  
  # Background image.
  #image = "fl_tech_background.jpg"  # Name of image in `static/img/`.
  #image_darken = 0.5  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  #image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  #image_parallax = false  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = false

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0px", "0px", "50px"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++
### **Fairness in AI**

<div>
<img style="float: right; margin:30px 30px" src="facial_recognition_action.jpg" height="300px" width="400px">
<font size="4">

**Convolutional neural networks** are typically trained with large datasets of 
labelled or unlabelled data. Collecting such data is expensive and time-consuming, 
and the datasets are often unbalanced, meaning that certain groups of categories 
are poorly represented in the data. Unbalanced dataset can have important negative 
consequences in the resulting models. For instance, facial recognition algorithms 
based on convolutional neural networks  tend to be very accurate for white, young 
male subjects. However, the models’ accuracy when applied to a people of color is 
often much lower. There is a significant interest for developing balanced datasets 
to train fair algorithms, and companies such as Google and IBM are investing significant 
resources to create these new datasets.
However, the problem is more challenging when dealing with clinical data, because 
collecting large datasets of clinical is often impossible due to the limited number 
of patients and privacy concerns. 

In this project, we will explore how new machine learning techniques such as transfer 
learning and generative-adversarial networks can help to mitigate the problem of 
algorithmic bias against clinical populations without requiring large databases of 
representative data.
</font>
<div>
