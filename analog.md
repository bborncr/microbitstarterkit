# Potentiometer

## Step 1 Connections

Connect the pot sensor to P0 on the moto:bit

## Step 2 Add the "Plot Bar Graph" block

From the "LED" blocks add the "plot bar graph" block to the forever loop.

```blocks
basic.forever(function () {
    led.plotBarGraph(
    0,
    0
    )
})
```

## Step 3 Add the Analog Read P0 block

From the Advanced-->Pins blocks add the "analog read pin P0" block to the first parameter. 
Put 1023 in the second parameter.

```blocks
basic.forever(function () {
    led.plotBarGraph(
    pins.analogReadPin(AnalogPin.P0),
    1023
    )
})
```

## Step 4 Upload the Code
Upload the Code
Pair the micro:bit and Download the code

## Step 5 Open the Device Console
Open the Device Console
Show console Device