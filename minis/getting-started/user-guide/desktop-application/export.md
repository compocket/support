# Export

The application provides the user with 4 different export option: **PNG, PDF,  CSV** and **MAT.**

### **PNG**

In the png section, you can select the source to get the screenshot. These sources can be Oscilloscope, FFT, XY Graph or Measurement.

![Export as PNG](../../../../.gitbook/assets/image%20%2896%29.png)

Refresh Data button enables you to get the latest screenshots of all the sources. You do not need to re-open the export window to refresh the sources.

Copy to Clipboard button make you copy the image without saving it.

### PDF

In the pdf section, this time, you can select multiple sources to add to the report. In addition, you can add captions for the images and tables.  

![Export as PDF](../../../../.gitbook/assets/image%20%2846%29.png)

As you select the sources, you will see that the selected source and its caption are written on the report in preview section.

Refresh Data button enables you to get the latest screenshots of all the sources.

### CSV

In the csv section, you can select the source as Oscilloscope, FFT or XY to get the data.

![Export as CSV](../../../../.gitbook/assets/image%20%28130%29.png)

{% hint style="info" %}
To see the time-domain values of the signal, it should be visible.

To see the frequency-domain values of the signal, it should be visible and "Show FFT" option should be selected for that signal.
{% endhint %}

Refresh Data button enables you to get the latest data of all the sources.

### MAT

In the mat section, you can select the oscilloscope for time-domain and FFT for frequency-domain to add them to the mat struct.

![Export as MAT](../../../../.gitbook/assets/image%20%28149%29.png)

If you export as **MAT**, the application creates a MAT file that includes a struct with a name "Signals". It includes 2 fields: **TimeDomain** and **FrequencyDomain**.  Both of them contain as many elements as the number of signals. 

Each struct in the TimeDomain field is a $$Nx1 $$ struct, where $$N$$ is the buffer length. Each element of the struct consists of **t** and **V** fields which correspond to time and voltage values respectively.

Each struct in the FrequencyDomain field is a $$nx1 $$ struct, where $$n = N/2+1$$. Each element of the struct consists of **f** and **dB** fields which correspond to frequency and amplitude values respectively.

![Exported mat struct](../../../../.gitbook/assets/image%20%2866%29.png)

Refresh Data button enables you to get the latest data of all the sources.

