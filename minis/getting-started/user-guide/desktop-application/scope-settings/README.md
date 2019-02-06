# Scope Settings

The scope is the most important part of the application. Here, you can observe the channels and math signals in the time domain. The scope is divided into 10 equal spaces both horizontally and vertically. Each interval in the horizontal line corresponds to **time/div**. Likewise, each interval in the vertical line corresponds to **volt/div**. 

![](../../../../../.gitbook/assets/image%20%289%29.png)

The left axis of the scope displays the values of the Channel-1 that intersect with the equally spaced horizontal line. The volt/div for the left axis is determined by the Channel-1. Similarly, the right axis is for the Channel-2. The volt/div for the right axis is determined by the Channel-2. The only difference is that if the mouse hovers over a signal different than channels, let's say S3, the right axis values are determined by S3. The time axis is a global axis. Every signal has the same time values. You can look at [**Volt/div & Time/div Settings**](volt-div-and-time-div-settings.md) ****to learn how to change these values.

In the above picture, there is a horizontal line vertically centered which is in the color of the Channel-1. This means, the oscilloscope is triggered according to the Channel-1 and the triggering value is determined as 0V. You can move this line, to change the trigger position vertically. For details, check [**Trigger**](trigger.md) ****page. 

Below the scope, you see some information about the graphic. You can see the **acquisition rate, sampling rate, buffer depth, ch1 and ch2 range.** 

Above the scope, there is a buffer navigator. It shows the complete buffer and highlights the visible part of the buffer. If you click the highlighted part and move the mouse, you can move the visible window of the buffer together with the mouse. If you click the other parts, you can directly go to the corresponding part of the buffer. To learn how to change the buffer settings, like sampling rate, real-time rate, fps rate, buffer depth, check [**Buffer Settings**](../buffer-settings.md).

The scope area has a context menu. This means, when you right click on the plot area, you will see a menu that help you to control some scope settings.

![](../../../../../.gitbook/assets/image%20%2823%29.png)

**Show Division Settings:** It will toggle the visibility of the labels that show the volt/div of each visible signals time time/div.  
**Lock volt offset:** If it is not selected, the center point of the zoom operation is the mouse location. If it is selected, the zoom operation is zero-centered.   
**Lock time offset:** If it is not selected, the center point of the zoom operation is the mouse location. If it is selected, the zoom operation is zero-centered.   
**Interpolation:** The default choice is **Linear**. This will connect the sample points with a line. If **None** is selected, the graph wil only displays the sample points. If **Sinc** is selected, the application applies sinc interpolation.  
**Show Frequency Domain:** This will control the visibility of the [**FFT**](../fft.md) graph.   
**Show XY Plot:** This will control the visibility of the [**XY Graph**](../xy-graph.md).

For now, you only see the right click control of the scope. The following subsections shows other control methods of the scope. In each section you may come across some shortcuts. To look all of them at once, check the page[ **Shortcuts.**](../shortcuts.md)\*\*\*\*

