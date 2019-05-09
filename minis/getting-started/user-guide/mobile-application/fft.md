# FFT

While observing the waveforms, you need not only the time-domain, but also the frequency-domain.  The FFT function produces a frequency-domain measurements. In the FFT graph, the vertical axis shows the amplitude whereas the horizontal axis shows the frequency. The graph uncovers the events that cannot be seen in the time domain. 

{% hint style="info" %}
To open the FFT window:  
    Click the Graph button.  
    Select **FFT**.
{% endhint %}

You can use the FFT for troubleshooting as well. If you expect a perfect sine wave for the signal, but you see some disturbance on it, you can check the FFT. If the signal is perfect sine-wave, there should be a clear peak only at the signal frequency. However, If you see another peak that cannot be ignored at different frequency, you can understand that something affects your source. 

{% hint style="warning" %}
The frequency range is calculated as:   
 $$[f_s/n , f_s/2]$$ where $$f_s$$ is sampling frequency, $$n$$ is buffer length
{% endhint %}

