# FFT

While observing the waveforms, you need not only the time-domain, but also the frequency-domain.  The FFT function produces a frequency-domain measurements. In the FFT graph, the vertical axis shows the amplitude whereas the horizontal axis shows the frequency. The graph uncovers the events that cannot be seen in the time domain. 

{% hint style="info" %}
To open the Frequency Domain window:  
   ![](../../../../.gitbook/assets/image%20%28116%29.png)   
    click on the FFT.

To show the FFT of a signal:  
    1\) Right click on the signal and select **"Show FFT"**.  
    2\) Enable **"Show FFT"** option from Channel Settings.

To add a cursor on the graph:  
    Double click on the graph.
{% endhint %}

![FFT of a 200 Hz square wave signal](../../../../.gitbook/assets/image%20%28162%29.png)

You can use the FFT for troubleshooting as well. If you expect a perfect sine wave for the signal, but you see some disturbance on it, you can check the FFT. If the signal is perfect sine-wave, there should be a clear peak only at the signal frequency. However, If you see another peak that cannot be ignored at different frequency, you can understand that something affects your source.  Below image illustrates this situation.

![A mixed signal](../../../../.gitbook/assets/image%20%28170%29.png)

The default window function is selected as **Rectangular.** You can select the window function to one of the followings by right clicking on the FFT window:

* Rectangular
* Triangular
* Hamming
* Hann
* Cosine
* Blackman Harris
* Flat Top
* Kaiser
* 
![](../../../../.gitbook/assets/image%20%28187%29.png)

{% hint style="warning" %}
The frequency range is calculated as:   
 $$[f_s/n , f_s/2]$$ where $$f_s$$ is sampling frequency, $$n$$ is buffer length
{% endhint %}



