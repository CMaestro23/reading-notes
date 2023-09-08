# 1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.

### The first influx of online videos and audio were made possible by proprietary plugin-based technologies like Flash and Silverlight. Both of these had security and accessibility issues, and are now obsolete, in favor of native HTML solutions <video> and <audio> elements and the availability of JavaScript APIs for controlling them.

# 2. Describe the use of the src and controls attributes in the <video> element.

### the src element contains a path to the video similar to the img tag. the control tag allows users to control the video, to start/stop, and control volume of the video.

# 3. Why is it important to have fallback content inside the <video> element?

### in case the browser can't support the video it allows a user to still access the content.

# 4. Write a very short story where <audio> and <video> are characters.

### <audio> and <video> walked into a bar. <video> showed <audio> how to duck and <audio> told <video> that there was a bar. 

# 1. How does Grid layout differ from Flex?

### Grid layout is best for two-dimensional layouts, while Flexbox is more suited for one-dimensional layouts - 

# 2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

### The grid container is an element in which you define a grid layout. It acts as a parent or a container for a set of grid items

### A grid item is an element that is a direct child of the grid container and becomes a part of the grid layout

### Grid lines are imaginary lines that form the horizontal and vertical divisions of a grid. They separate the grid rows and columns, defining the structure of the grid layout.

# 1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

### essentially it helps the page compatible and work well with different types of screens. Whether its mobile, desktop or other formats to view a webpage.

# 2. Define the following <img> attributes srcset and sizes. Write an example of how they are used.

### The srcset attribute specifies a list of image files and their respective sizes or descriptors.
### The sizes attribute defines the width of the image element as a percentage of the viewport width (vw) or a fixed width in pixels (px).
### Together, the srcset and sizes attributes allow web developers to provide multiple image sources and guide the browser in choosing the appropriate source and size for responsive web design, optimizing both image quality and performance for different devices and screen sizes.

# 3. How is srcset more helpful for responsive images than CSS or JavaScript?

### is an HTML attribute used for responsive images that allows web developers to provide multiple image sources in different resolutions or sizes. It is particularly helpful for responsive design because it offers several advantages over using CSS or JavaScript for handling responsive images.