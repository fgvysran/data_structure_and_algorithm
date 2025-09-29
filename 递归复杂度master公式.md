# 递归复杂度master公式

T(N) = a * T(N / b) + O(N^d)

if(log(b,a) < d) 复杂度:O(N^d)

else if ( > d) 复杂度N^log(b,a)

else 复杂度:(N^d) * logN



#### egg:

merge_sort:T(N) = 2 * T(N / 2) + O(N^1)

log(2,2) == 1

时间复杂度:(N ^ d)    * log(N)


