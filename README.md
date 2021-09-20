# Python Projects: Calculate Python Code 🐍
This repo contains python code that how long it takes for your Python code to execute.<br>
Run the code.


Python
```python
import time
start_time = time.time()

for a in range(0,10000):
    for b in range(0, 10000):
        pass

end_time = time.time()

print('How long did it take? ')
print(f"It took: {end_time - start_time:3f} seconds")

```

Output
```python
How long did it take? 
It took: 3.749114 seconds
```
