# Learning-Python
Day 1
# -*- coding: utf-8 -*-

#定义函数


def calc(numbers):
    s = 0
    for n in numbers:
        n = float(n)
        s = s + n * n
    return s

#main
ss = input('请输入您要计算的数字,用逗号将数字隔开\n')
numbers = ss.split(',')

print(calc(numbers))

