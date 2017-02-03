# 368_3_TempConversionWithDelegates

1. Using the conversion methods and a `Dictionary`, (and `TempScale` enum, of course) re-implement the Universal Converter method:

```csharp
public static double ConvertTemperature(double degrees, TempScale from, TempScale to)

```

1. Assuming you have a mapping of units to other unit (e.g. 1 yard = 3 feet, 1 foot = 12 inch, 1 inch = 2.54 cm), how can you implement a program to cnvert from _any_ unit to _any other_ unit which is theoretically possible. For example, given that the distance from earth to the moon is 238,900 miles and a hotdog is 8 inches (and 1 mile = 5280 ft, 1 ft= 12 inches) your program should convert from moon-earth distance to hotdogs.

This should be implemented without hardcoding every possible combination of conversions. If new data arrives (e.g. distance from Earth to alpha centari is 4.3 light years, the program should not have to rewritten and compiled...it is just more data and the program should be able to adapt.

The important question is to _**represent**_ the conversion properly. Once done, the rest is much simpler 

Add link to travis
