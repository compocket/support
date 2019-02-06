# Advanced Functions

As we said before, we try to give as much control as possible to the user. Giving only simple math operations is not enough for us. That's why we created the **Functions** page in which user can use advanced math operations with block diagram.

![](../../../../.gitbook/assets/image%20%2840%29.png)

{% hint style="info" %}
To use the blocks, you need to drag them to the area.  
To change the settings of the block, you need to right click on it.
{% endhint %}

**Inputs**

\*\*\*\*![](../../../../.gitbook/assets/image%20%288%29.png) : You can select a signal as input and determine the gain. 

![](../../../../.gitbook/assets/image%20%2849%29.png) : It gives a dc signal with a desired offset.

![](../../../../.gitbook/assets/image%20%2814%29.png) : It gives a sine signal with a desired offset, amplitude, phase and frequency.

![](../../../../.gitbook/assets/image%20%2836%29.png) : It gives a cosine signal with a desired offset, amplitude, phase and frequency.

![](../../../../.gitbook/assets/image%20%2828%29.png) : It gives a square signal with a desired offset, amplitude, phase and frequency.

**Functions**

\*\*\*\*![](../../../../.gitbook/assets/image%20%2845%29.png) : The basic operations. All of them take 2 inputs.  

![](../../../../.gitbook/assets/image%20%2826%29.png) : Logic AND gate. It takes 2 inputs.

![](../../../../.gitbook/assets/image%20%2848%29.png) : Logic NAND gate. It takes 2 inputs.

![](../../../../.gitbook/assets/image%20%2831%29.png) : Logic OR gate. It takes 2 inputs.

![](../../../../.gitbook/assets/image%20%2822%29.png) : Logic NOR gate. It takes 2 inputs.

![](../../../../.gitbook/assets/image%20%2824%29.png) : Logic XOR gate. It takes 2 inputs.

![](../../../../.gitbook/assets/image%20%2837%29.png) : Logic XNOR gate. It takes 2 inputs.

![](../../../../.gitbook/assets/image%20%2850%29.png) : Logic NOT gate. It takes only 1 input.

{% hint style="info" %}
All the logic gates have 4 features in common. You can set the VCC+, VCC- , HIGH voltage and LOW voltage for every logic gate. 

If the input value is between LOW and VCC-, it is considered as logic 0. If the input value is between HIGH and VCC+, it is considered as logic 1. The values between LOW and HIGH are considered as indeterminate. 

If the output of the logic is 1, corresponding analog value is VCC+. If the output of the logic is 0, corresponding analog value is VCC-.
{% endhint %}

![](../../../../.gitbook/assets/image%20%2839%29.png) : Comparator. If Input1 &gt; Input2, the output is VCC+, otherwise VCC-.

![](../../../../.gitbook/assets/image.png) : Inverting Schmitt Trigger. 

![](../../../../.gitbook/assets/image%20%2811%29.png) : Non-inverting Schmitt Trigger.

