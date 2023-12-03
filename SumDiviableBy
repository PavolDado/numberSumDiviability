def diviable_by(start, stop, divisor):
    '''
    returns array of numbers between start and stop
    that sum of each number is diviable by divisor
    '''
    tmp_arr = []
    for i in range(start, stop):
        tmp_val = str(i)
        tmp_arr_val = 0
        for tmp_number in tmp_val:
            tmp_arr_val += int(tmp_number)
        if tmp_arr_val % divisor == 0:
            tmp_arr.append(tmp_val)
    return tmp_arr
