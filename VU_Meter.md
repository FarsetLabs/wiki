An analogue needle for when style and charm are more important than accurate
readings.

Powering this thing is as simple as making a [potential divider] circuit. The
meter has an internal resistance of approximately 1.1 kΩ and a full scale
deflection at 3 mV.

Arduino Implementation
----------------------

<img src="http://wiki.farsetlabs.org.uk/w/images/f/fd/Vumeter_rationalfit.png" alt="Mapping between the Arduino analogue out and the numbers on the VU meter." style="width: 350px;"/>

If one wishes to use this in conjunction with something like the Arduino, which
has a maximum of 5 V on the analogue output, you will need to pair the meter
with a resistor of roughly 16 kΩ.

While the meter has numbers from -20 to +5, the analogue output runs from 0 to
255 and the mapping between these two is of course non-linear as can be seen in
the lovely figure to the left.

### Maths

The [rational function model] for this mapping is as follows.

$$y = \frac{1107x + 20860} {x^{2} - 19.91x + 190.9}$$

### Arduino Code

Use this to get an analogue out for whatever arbitrary value between -20 and 5
you specify.

``` {.C}
    int vuMapping(float value){
        float p1 = 1107;
        float p2 = 20860;
        float q1 = -19.91;
        float q2 = 190.9;
        pwmValue = (int)( (p1*value + p2) / (value*value + q1*value + q2) );

        if (pwmValue < 0){
            pwmValue = 0;
        }

        return(pwmValue);
    }
```

[potential divider]: http://en.wikipedia.org/wiki/Potential_divider
[rational function model]: http://en.wikipedia.org/wiki/Polynomial_and_rational_function_modeling#Rational_function_models
