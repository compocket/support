# Preferences

As we said before, we try to make the application as flexible as possible for the users. In the **Preference** window, you can change the **appearance** and **control settings.**

{% hint style="info" %}
As you make changes, you can see the effects in real-time.
{% endhint %}

![Appearance](../../../../.gitbook/assets/image%20%2840%29.png)

### Appearance

**Border Color:** The common color of the borders of the buffer navigator, oscilloscope, fft graph and xy graph.  
**Background Grid Color:** The common color of the grid lines in the oscilloscope, fft graph and xy graph.  
**Background Color:** The common color of the backgrounds of the buffer navigator, oscilloscope, fft graph and xy graph.  
**Cursor & Text Color:** The color of the cursors and global axes' texts.  
**Background Grid Thickness:** The thickness of the grid lines.  
**Background Frame Thickness:** The thickness of the borders.  
**Trace Thickness:** The thickness of the waveform.  
**Selected Trace Thickness:** The thickness of the selected/highlighted waveform.  
**Cursor Thickness:** The thickness of the cursors.

![Control Settings](../../../../.gitbook/assets/image%20%2857%29.png)

### Control Settings

**Language:** You can change the language of the application. For now, we only support English and Turkish.  
**10MSPS:** As indicated in the warning, this feature is useful when you observe signals with a frequency higher than 200 kHz. Below that frequency limit, this feature may lead you to experience some bugs.   
**Average:** It is useful to deal with noisy data. However it decreases the number of frames per second.  
**Persistence:** This mode enables the application to show the previous waveforms. This is generally used for observing complex or varying waveforms and can help to make disturbances visible.  
**Performance:** It is related to number of frames in seconds. The default value is **HIGH.** If you do not have a powerful PC, the application may flicker. In this case, try to change the performance to **NORMAL** or **LOW.**

{% hint style="info" %}
If you select the **"Save the preferences for later use"** checkbox, the changes are made permanently.

To save the changes you made, click **Save** button.

If you want to reset the changes, you can click **"Reset to default values".**
{% endhint %}

