# filter-prime
def not_prime(n):
    if n == 1:
        return 1
    else:
        for i in xrange(2,int(n**0.5+1)):
            if n%i == 0:
                return 1
        else:
            return 0

s = [i for i in range(1,100)]
print filter(not_prime,s)


输出：
C:\Python27\python.exe C:/Users/Administrator/PycharmProjects/Py_1/function_my.py
[1, 4, 6, 8, 9, 10, 12, 14, 15, 16, 18, 20, 21, 22, 24, 25, 26, 27, 28, 30, 32, 33, 34, 35, 36, 38, 39, 40, 42, 44, 45, 46, 48, 49, 50, 51, 52, 54, 55, 56, 57, 58, 60, 62, 63, 64, 65, 66, 68, 69, 70, 72, 74, 75, 76, 77, 78, 80, 81, 82, 84, 85, 86, 87, 88, 90, 91, 92, 93, 94, 95, 96, 98, 99]

Process finished with exit code 0
