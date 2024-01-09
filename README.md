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

    Binary (YET TO BE IMPLEMENTED)
    
    Decimal (YET TO BE IMPLEMENTED)
    
    Hexadecimal (YET TO BE IMPLEMENTED)
    
    Two's complement (YET TO BE IMPLEMENTED)
    
    Floating (YET TO BE IMPLEMENTED)
    
    Fixed point (YET TO BE IMPLEMENTED)
    
    Multiplication (YET TO BE IMPLEMENTED)
    
    Division (YET TO BE IMPLEMENTED)
    
    Addition (YET TO BE IMPLEMENTED)
    
    Subtraction (YET TO BE IMPLEMENTED)
    
Capacitors

    Miller’s Theorem (YET TO BE IMPLEMENTED)
    
    Series (YET TO BE IMPLEMENTED)
    
    Parallel (YET TO BE IMPLEMENTED)
    
    Combined (YET TO BE IMPLEMENTED)
    
Circuit Analysis

    RLC (YET TO BE IMPLEMENTED)
    
    RC (YET TO BE IMPLEMENTED)
    
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
      
      Missing value (YET TO BE IMPLEMENTED)
      
Complex Numbers

    Rectangular (YET TO BE IMPLEMENTED)
    
    Polar (YET TO BE IMPLEMENTED)
    
Diodes

    Ideal diode (YET TO BE IMPLEMENTED)
    
    Current (YET TO BE IMPLEMENTED)
    
    Voltage drop (YET TO BE IMPLEMENTED)
    
    Etc (YET TO BE IMPLEMENTED)
    
Error Analysis

    Margin of Error (YET TO BE IMPLEMENTED)
    
    Tolerance (YET TO BE IMPLEMENTED)
    
    Tolerance Range (YET TO BE IMPLEMENTED)
    
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

    Series (YET TO BE IMPLEMENTED)
    
    Parallel (YET TO BE IMPLEMENTED)
    
    Combined (YET TO BE IMPLEMENTED)
    
Op Amps

    Inverting (YET TO BE IMPLEMENTED)
    
    Non-inverting (YET TO BE IMPLEMENTED)
    
    Etc (YET TO BE IMPLEMENTED)
    
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
        
    Combined (YET TO BE IMPLEMENTED)
    
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
            
    Frequency Response (YET TO BE IMPLEMENTED)
    
    Period (YET TO BE IMPLEMENTED)
    
    Frequency (YET TO BE IMPLEMENTED)
    
Signal Processing

    Convolution (YET TO BE IMPLEMENTED)
    
    Filtering (YET TO BE IMPLEMENTED)
    
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
    
        Voltage (YET TO BE IMPLEMENTED)
        
        Current (YET TO BE IMPLEMENTED)
        
    Dependent Sources
    
        Voltage (YET TO BE IMPLEMENTED)
        
        Current (YET TO BE IMPLEMENTED)
        
Transistors

    Pmos (YET TO BE IMPLEMENTED)
    
    Nmos (YET TO BE IMPLEMENTED)
    
    Regimes (YET TO BE IMPLEMENTED)
    
    Kp (YET TO BE IMPLEMENTED)
    
    Ucox (YET TO BE IMPLEMENTED)
    
    L (YET TO BE IMPLEMENTED)
    
    W (YET TO BE IMPLEMENTED)
    
    Gm (YET TO BE IMPLEMENTED)
    
    Id (YET TO BE IMPLEMENTED)
    
