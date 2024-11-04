# Big Decimal
*临时记录：
1.两个BigDecimal类进行等值对比时，用compareTo(),不要用equals()。前者要对比精度，可能会出现错误情况，后者要忽略精度。
2.*