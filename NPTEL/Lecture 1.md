### Lecture 1

# Introduction to Digital Circuits

- **Signals**: Signal is a variation in physical parameter, temperature variation is a signal, speech, video is a signal (light intensity variation).

  - *wik*i:

    In [signal processing](https://en.wikipedia.org/wiki/Signal_processing), a **signal** **is a function that conveys [information](https://en.wikipedia.org/wiki/Information) about a phenomenon**. In electronics and telecommunications, it refers to any time varying [voltage](https://en.wikipedia.org/wiki/Voltage), [current](https://en.wikipedia.org/wiki/Electric_current) or [electromagnetic wave](https://en.wikipedia.org/wiki/Electromagnetic_wave) that carries information. A signal may also be defined as an **observable change in a quantity**.

  

- > A Signal is defined as a variation in electrical quantity usually a voltage or a current with time.
  >
  > An electrical quantity which does not change with time is no more referred to as a signal, it is a DC value. If we know that its value is not going to change with time then there is no need for processing, you know the value therefore you can use it where ever you want to use it.



- The device which converts non electrical quantity into an electrical quantity/signal is called a ***Transducer***.

- The output of a transducer is an electrical signal, where we define the signal as the variation of the parameter of interest i.e. voltage or current with time.

- Normally a signal can take any value within a limit at different instances of time.

  ![](https://imgur.com/ItmSwEF.png)

  

  An **Analog Signal** can take any value at any instant of time, within the defined limit/ specified range.



- We can discretize the time at which we observe the value of the signal. The signal will vary continuously all the time but we are looking at discrete instants of time.

  ![](https://imgur.com/2dT7cAH.png)

  When we observe the signals at discrete instants of time then it is called **Discrete time signal**.

  > A signal has no meaning until we use it somewhere.

  - Consider the case where the limit/ range of the signal is from 0 to 5 Volts. Theoretically the signal can take infinite number of levels between 0 and 5 volts.

  - When we transmit the signal, how accurately can we represent the signal's variation between 0 and 5 volts (Note: Signal can take infinite values between 0 and 5 volts).

  - Originally we had a signal with continuous time and amplitude variation. Then we let the amplitude continuously vary and discretize the time. We will now introduce discretization in the amplitude as well by allowing the signal to take only a specific number of discrete levels.

  - When we discretize the amplitude in addition to dicretizing the time, such a signal is called **Digital Signal**.

    ![](https://imgur.com/zw4y4Ha.png)

    @15.00

