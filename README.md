# -


def Func (a,func_b):
    b = func_b - 1
    import time
    a_dictionary = {}
    for i in range(0,a):
        a_dictionary[int(time.time()*1000000000)] = 0
        time.sleep(0.001)
    for n in range(0,b):
        for key in a_dictionary:
            a_dictionary[key] += 1
        math = 0
        for key,value in a_dictionary.items():
            if value >= 2:
                math += 1
        for ii in range (0,math):
            a_dictionary[int(time.time()*1000000000)] = 0
            time.sleep(0.001)
    print(len(a_dictionary))
    print(a_dictionary)

    #求分裂问题，感兴趣的我就把分裂时间也设成可自定义的，感兴趣的留言
