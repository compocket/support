# Oscilloscope Settings

The oscilloscope is the most important part of the application. Here, you can observe the channels and math signals in the time domain. The scope is divided into 10 equal spaces both horizontally and vertically. Each interval in the horizontal line corresponds to **time/div**. Likewise, each interval in the vertical line corresponds to **volt/div**. 

![](../../../../../.gitbook/assets/image%20%28161%29.png)

The left axis of the oscilloscope displays the values of the Channel-1 that intersect with the equally spaced horizontal lines. The volt/div for the left axis is determined by the Channel-1. Similarly, the right axis is for the Channel-2. The volt/div for the right axis is determined by the Channel-2. The only difference is that if you select a signal different than channels, let's say S3, the right axis values are determined by S3. The time axis is a global axis. Every signal has the same time values. You can look at [**Volt/div & Time/div Settings**](volt-div-and-time-div-settings.md) ****to learn how to change these values.

![The view when the yellow colored signal selected](../../../../../.gitbook/assets/image%20%2866%29.png)

If you select a signal\(by tapping on it\), you can see the values of the selected signal where it intersects with the equally spaced vertical lines.

You can drag the signals horizontally and vertically with the finger movements. If you select the signal the vertical movement only affects that signal. Horizontal movement affect all of them. The reason for this difference is that every signal has its own volt offset while the time offset is common.

In the above pictures, there is a horizontal line vertically centered which is in the color of the Channel-1. This means, the oscilloscope is triggered according to the Channel-1 and the triggering level is determined as 0V. You can move this line from the left and the right axes to change the trigger position vertically. For details, check [**Trigger**](trigger.md) ****page. 

Below the oscilloscope, you see some information about the graphic. You can see the **acquisition rate, sampling rate** and **buffer depth.** 

Above the oscilloscope, there is a buffer navigator. It shows the complete buffer and highlights the visible part of the buffer. If you drag the highlighted part, you can move the visible window of the buffer. If you touch the other parts, you can directly go to the corresponding part of the buffer. To learn how to change the buffer settings, like sampling rate, fps rate, buffer depth, check [**Buffer Settings**](../buffer-settings.md).

![The menu for the graphs](../../../../../.gitbook/assets/image%20%285%29.png)

When the graph button is clicked, it opens a menu in which you can select the graphs that you want to observe.

![The view when all the graphs are selected](../../../../../.gitbook/assets/image%20%28118%29.png)

If you select all of the graphs, the application show all of them at the same time. 

