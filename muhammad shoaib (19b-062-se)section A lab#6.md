
# Muhammad Shoaib (19b_062_se) lab#5


```python
import time

a = time.strftime('%A %b %d %I:%M %p', time.localtime())
print(a)

b = time.strftime('%I:%M %p Central Daylight Time on %b /%d/%y', time.localtime())
print(b)

c = time.strftime('I will meet you on Thu %b %d at %I:%M %p', time.localtime())
print(c)
```

    Tuesday Nov 26 01:15 PM
    01:15 PM Central Daylight Time on Nov /26/19
    I will meet you on Thu Nov 26 at 01:15 PM
    


```python
forecast = 'It will be a sunny day today'
print(forecast)
print("day is ",forecast.count('day'),"times")
print("index of sunny is: ",forecast.find('sunny'))
print(forecast.replace('sunny', 'cloudy'))
```

    It will be a sunny day today
    day is  2 times
    index of sunny is:  13
    It will be a cloudy day today
    


```python
n = int(input("Enter range: "))
for i in range(2,n):
    if  i % 2 == 0 or i % 3 == 0:
        print(i)
    
```

    Enter range: 13
    2
    3
    4
    6
    8
    9
    10
    12
    


```python
first = str('Syed Faisal')
last = str('ALI')
city = str('Karachi')
department = str('Computer scienc')
Zip = str('Gulshan e Iqbal, 75300')
institute = str('Usman institute of technology')
print('\t\t',"Maling")
print("\t\t")
print(first,"",last,'\n',department,'\n',institute,'\n',Zip,'\n',city)

```

    		 Maling
    		
    Syed Faisal  ALI 
     Computer scienc 
     Usman institute of technology 
     Gulshan e Iqbal, 75300 
     Karachi
    


```python
dictionary = {'1':'jan','2':'feb','3':'mar','4':'apr','5':'may','6':'jun','7':'july','8':'aug','9':'sep','10':'oct','11':'nov','12':'dec'}
print(dictionary['1'])
```

    jan
    
