# python
#小试身手
#学习python
def lists(a_list):
    n=0
    a=len(a_list)
    b=[]
    while a>n:    
        b.insert(n,len(str(a_list[n]//1)))
        n+=1    
    d=0
    while a>d:
        m=int(max(b))-int(b[d])
        print(' '*m+str(a_list[d]))
        d+=1



lists([-3.14,0.7177,1586.23,10000.0,-587643.1,12.34565])
