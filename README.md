# -42.-find-the-largest-number-from-the-list-of-the-numbers-entered-through-keyboard.
n=int(input("enter the limit less than 99999999999 "))
small=99999999999
for i in range(1,n+1):
    print("enter ",i,end='')
    a=int(input("th number : "))
    if a<small:
        small=a
        print("smallest no. is ",small)

OUTPUT
enter the limit less than 99999999999 8
enter  1th number : 11
smallest no. is  11
enter  2th number : 22
enter  3th number : 33
enter  4th number : 44
enter  5th number : 55
enter  6th number : 66
enter  7th number : 77
