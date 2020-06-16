# SORRY
import sys
sys.setrecursionlimit(1004)
print(sys.getrecursionlimit())
i=0
def sorry():
    global i
    i+=1
    print('SORRY', i)
    sorry()
sorry()
