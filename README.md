IMPORTANT NOTE:
1) This repository is ACTIVELY being updated and represents a WORK IN PROGRESS. Please check again tomorrow if you see something wrong and likely the issue will already have been fixed. :)

2) I create these programs/functions in my free time and they do not represent any professional development.
They are not perfect, and although I carefully aim to create good programs, they will have mistakes and quirks.
IF YOU SEE ANY MISTAKES OR WOULD LIKE TO CONTRIBUTE, PLEASE email me at electricalengineeringexpanded@gmail.com.
I am constantly learning and hope to create better quality programs in the future.
Sincerely,
jaredsbror :)

EEE_Windows.tns - Generates Windowing functions which, in conjunction with convolution (not yet implemented), can serve to frame and extract signal data

EEE_Energy.tns - Used to calculate the energy of both discrete-time and continuous-time signals

EEE_Power.tns - Used to calculate the power of both discrete-time and continuous-time, periodic signals

EEE_Functions.tns - Used to generate function definitions for unit step (heaviside) functions, as well as rect, triangle, and sinc functions

EEE_Mag.tns - (NOTE: Somewhat buggy) Used to determine the magnitude response of a pole/zero plot in both Laplace and Z-Domain

EEE_Resistors.tns - (1) Determine parallel resistance (2) Determine which missing resistor value produces a specific equivalent resistance

EEE_CircValues.tns ("circuit values") - Determine the power, current, voltage, and resistance via basic equations

EEE_Distance.tns - (Still in testing) Calculate the distance between two complex points in the complex plane


COMPLETE VISION OF FUNCTIONS/PROGRAMS TO BE CREATED
Base Conversions/Functions
    Binary (IN PROGRESS)
    Decimal (IN PROGRESS)
    Hexadecimal (IN PROGRESS)
    Two's complement (IN PROGRESS)
    Floating (IN PROGRESS)
    Fixed point (IN PROGRESS)
    Multiplication (IN PROGRESS)
    Division (IN PROGRESS)
    Addition (IN PROGRESS)
    Subtraction (IN PROGRESS)
Capacitors
    Miller’s Theorem (IN PROGRESS)
    Series (IN PROGRESS)
    Parallel (IN PROGRESS)
    Combined (IN PROGRESS)
Circuit Analysis
    RLC (IN PROGRESS)
    RC (IN PROGRESS)
Circuit Values
    Voltage
        voltage(i,r)
        (avgvoltage)
        voltagedrop(voltage,resistorlist)
  Current
        current(v,r)
        (avgcurrent)
        totalcurrent(voltage,resistorlist)
  Resistance
      resistance(v,i)
  Power
      power()
      Missing value (IN PROGRESS)
Complex Numbers
    Rectangular (IN PROGRESS)
    Polar (IN PROGRESS)
Diodes
    Ideal diode (IN PROGRESS)
    Current (IN PROGRESS)
    Voltage drop (IN PROGRESS)
    Etc (IN PROGRESS)
Error Analysis
    Margin of Error (IN PROGRESS)
    Tolerance (IN PROGRESS)
    Tolerance Range (IN PROGRESS)
Functions
    Heaviside
        u(modifier)
        umod(function,modifier)
        uswitch(function,switchpoint)
        ubound(function,leftbound,rightbound)
    Triangle
        tri(modifier)
    Rect
        rect(modifier)
    Sinc
        sinc(modifier)
Inductors
    Series (IN PROGRESS)
    Parallel (IN PROGRESS)
    Combined (IN PROGRESS)
Op Amps
    Inverting (IN PROGRESS)
    Non-inverting (IN PROGRESS)
    Etc (IN PROGRESS)
Resistors
    Series
        solveseries()
    Parallel
        paralel(list)
        parallel2(a,b)
        parallel3(a,b,c)
        parallel4(a,b,c,d)
        parallel5(a,b,c,d,e)
        parallel6(a,b,c,d,e,f)
        solveparallel()
    Combined (IN PROGRESS)
Signal Characteristics
    Power
        Discrete-time
            powd(period,fx)
            powdsum(array)
    Continuous-time
        powc(period,fx)
    Energy
        Discrete-time
            engd(fx,lower,upper)
            engd2(fx1,lower1,upper1,fx2,lower2,upper2)
            engd3(fx1,lower1,upper1,fx2,lower2,upper2,fx3,lower3,upper3)
            engd4(fx1,lower1,upper1,fx2,lower2,upper2,fx3,lower3,upper3,fx4,lower4,upper4)
            engdsum(array)
        Continuous-time
            engc(fx,lower,upper)
            engc2(fx1,lower1,upper1,fx2,lower2,upper2)
            engc3(fx1,lower1,upper1,fx2,lower2,upper2,fx3,lower3,upper3)
            engc4(fx1,lower1,upper1,fx2,lower2,upper2,fx3,lower3,upper3,fx4,lower4,upper4)
            Magnitude Response
            magz()
            mags()
    Frequency Response (IN PROGRESS)
    Period (IN PROGRESS)
    Frequency (IN PROGRESS)
Signal Processing
    Convolution (IN PROGRESS)
    Filtering (IN PROGRESS)
Windowing
    bartlett(length)
    blackman(length)
    blackmanharris(length)
    hamming(length)
    hanning(length)
    lanczos(length)
    nutall(length)
    rectangle(length)
Sources
    Independent Sources
        Voltage (IN PROGRESS)
        Current (IN PROGRESS)
    Dependent Sources
        Voltage (IN PROGRESS)
        Current (IN PROGRESS)
Transistors
    Pmos (IN PROGRESS)
    Nmos (IN PROGRESS)
    Regimes (IN PROGRESS)
    Kp (IN PROGRESS)
    Ucox (IN PROGRESS)
    L (IN PROGRESS)
    W (IN PROGRESS)
    Gm (IN PROGRESS)
    Id (IN PROGRESS)
