# FFT

While observing the waveforms, you need not only the time-domain, but also the frequency-domain.  The FFT function produces a frequency-domain measurements. In the FFT graph, the vertical axis shows the amplitude whereas the horizontal axis shows the frequency. The graph uncovers the events that cannot be seen in the time domain. 

{% hint style="info" %}
To open the Frequency Domain window:  
    Right click on the Scope area.  
    Select **"Show Frequency Domain"**.

To show the FFT of a signal:  
    Right click on the signal.  
    Select **"Show FFT"**.

To add a cursor on the graph:  
    Double click on the graph.
{% endhint %}

![FFT of a 200 Hz square wave signal](../../../../.gitbook/assets/image%20%2832%29.png)

You can use the FFT for troubleshooting as well. If you expect a perfect sine wave for the signal, but you see some disturbance on it, you can check the FFT. If the signal is perfect sine-wave, there should be a clear peak only at the signal frequency. However, If you see another peak that cannot be ignored at different frequency, you can understand that something affects your source. 

![A mixed signal](../../../../.gitbook/assets/image%20%2836%29.png)

