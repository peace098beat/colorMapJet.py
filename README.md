# colorMapJet.py
```py
from colorMatJet import getColorJetRGBi, getColorJetRGBf
getColorJetRGBi(v=i / 100., vmin=0, vmax=1)
```

## example
```py
>> for i in range(0, 10):
>>   print i / 100., getColorJetRGBi(v=i / 100., vmin=0, vmax=1)
>> 0.0 [0, 0, 255]
>> 0.01 [0, 10, 255]
>> 0.02 [0, 20, 255]
>> 0.03 [0, 30, 255]
>> 0.04 [0, 40, 255]
>> 0.05 [0, 51, 255]
>> 0.06 [0, 61, 255]
>> 0.07 [0, 71, 255]
>> 0.08 [0, 81, 255]
>> 0.09 [0, 91, 255]

>> for i in range(0, 10):
>>   print  i / 100., getColorJetRGBf(v=i / 100., vmin=0, vmax=1)
>> 0.0 [0, 0.0, 1.0]
>> 0.01 [0, 0.04, 1.0]
>> 0.02 [0, 0.08, 1.0]
>> 0.03 [0, 0.12, 1.0]
>> 0.04 [0, 0.16, 1.0]
>> 0.05 [0, 0.2, 1.0]
>> 0.06 [0, 0.24, 1.0]
>> 0.07 [0, 0.28, 1.0]
>> 0.08 [0, 0.32, 1.0]
>> 0.09 [0, 0.36, 1.0]
```
