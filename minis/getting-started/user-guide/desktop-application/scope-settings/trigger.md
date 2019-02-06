# Trigger

The trigger function for the oscilloscope enables repetitive waveforms to be displayed on the screen in steady fashion instead of moving pictures. The trigger enables the timebase to start its scan at the same point on each repetition of the waveform. If this functionality is not used, the waveform starts at different voltage values for different frames which leads to meaningless observations.

For our platform, you can select the trigger source as Channel-1 or Channel-2. You can determine the trigger mode also. We have 3 different modes which are **auto, normal** and **single**.   
  
In the auto mode, the device tries to trigger the waveform continuously according to the trigger source, trigger voltage and trigger edge. If it triggers, the device sends the triggered waveform. If it cannot trigger, it send the waveform nevertheless. For the normal mode, the device does not send the waveform until it can trigger the waveform. In the single mode, the device sends the triggered waveform just once.   
  
In addition to trigger mode, you can also select the trigger edge as **rising** and **falling**. 

![](../../../../../.gitbook/assets/image%20%281%29.png)

You can change the trigger settings from this user interface. 

![](../../../../../.gitbook/assets/image%20%2828%29.png)

Or alternatively, you can right click on the channel waveform and change the trigger settings.

