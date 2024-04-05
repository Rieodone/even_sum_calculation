# even_sum_calculation
# just for calculate
# 生成0到10000的数字列表
numbers = list(range(10001))

# 从小到大排序
numbers.sort()

# 分别统计偶数和奇数的和
even_sum = sum([x for x in numbers if x % 2 == 0])
odd_sum = sum([x for x in numbers if x % 2 != 0])

# 计算结果
result = even_sum * odd_sum

print("所有偶数的和与所有奇数的和的乘积为:", result)
