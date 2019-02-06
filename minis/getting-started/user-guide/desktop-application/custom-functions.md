# Advanced Functions

As we said before, we try to give as much control as possible to the user. Giving only simple math operations is not enough for us. That's why we created the **Functions** page in which user can use advanced math operations with block diagram.

![](../../../../.gitbook/assets/image%20%2843%29.png)

{% hint style="info" %}
To use the blocks, you need to drag them to the area.  
To change the settings of the block, you need to right click on it.
{% endhint %}

### **Inputs**

\*\*\*\*![](../../../../.gitbook/assets/image%20%288%29.png) : You can select a signal as input and determine the gain. 

![](../../../../.gitbook/assets/image%20%2853%29.png) : It gives a dc signal with a desired offset.

![](../../../../.gitbook/assets/image%20%2814%29.png) : It gives a sine signal with a desired offset, amplitude, phase and frequency.

![](../../../../.gitbook/assets/image%20%2839%29.png) : It gives a cosine signal with a desired offset, amplitude, phase and frequency.

![](../../../../.gitbook/assets/image%20%2830%29.png) : It gives a square signal with a desired offset, amplitude, phase and frequency.

### **Functions**

\*\*\*\*![](../../../../.gitbook/assets/image%20%2848%29.png) : The basic operations. All of them take 2 inputs.  

![](../../../../.gitbook/assets/image%20%2828%29.png) : Logic AND gate. It takes 2 inputs.

![](../../../../.gitbook/assets/image%20%2851%29.png) : Logic NAND gate. It takes 2 inputs.

![](../../../../.gitbook/assets/image%20%2833%29.png) : Logic OR gate. It takes 2 inputs.

![](../../../../.gitbook/assets/image%20%2824%29.png) : Logic NOR gate. It takes 2 inputs.

![](../../../../.gitbook/assets/image%20%2826%29.png) : Logic XOR gate. It takes 2 inputs.

![](../../../../.gitbook/assets/image%20%2840%29.png) : Logic XNOR gate. It takes 2 inputs.

![](../../../../.gitbook/assets/image%20%2854%29.png) : Logic NOT gate. It takes only 1 input.

{% hint style="info" %}
All the logic gates have 4 features in common. You can set the VCC+, VCC- , HIGH voltage and LOW voltage for every logic gate. 

If the input value is between LOW and VCC-, it is considered as logic 0. If the input value is between HIGH and VCC+, it is considered as logic 1. The values between LOW and HIGH are considered as indeterminate. 

If the output of the logic is 1, corresponding analog value is VCC+. If the output of the logic is 0, corresponding analog value is VCC-.
{% endhint %}

![](../../../../.gitbook/assets/image%20%2842%29.png) : Comparator. If Input1 &gt; Input2, the output is VCC+, otherwise VCC-.

![](../../../../.gitbook/assets/image.png) : Inverting Schmitt Trigger. 

![](../../../../.gitbook/assets/image%20%2811%29.png) : Non-inverting Schmitt Trigger.

![Inverting and Noninverting Schmitt Trigger Diagrams](../../../../.gitbook/assets/untitled-diagram.png)

### **Filters**

![](../../../../.gitbook/assets/image%20%2816%29.png) : Low Pass Filter.

![](../../../../.gitbook/assets/image%20%2859%29.png) : High Pass Filter.

![](../../../../.gitbook/assets/image%20%2852%29.png) : Band Pass Filter.

![](../../../../.gitbook/assets/image%20%2820%29.png) : Band Stop Filter.

{% hint style="info" %}
All the filters are Butterworth filter.   
For LPF and HPF, you can select the order and the cut-off frequency.  
For BPF and BSF, you can select the order, the centeral frequency and the bandwidth.
{% endhint %}

### Outputs

![](../../../../.gitbook/assets/image%20%2838%29.png) : The output. To complete the block diagram, you need to add this block to the end. Every out block corresponds a new signal.

