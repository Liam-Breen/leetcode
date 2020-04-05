class Solution:
    def reverse(self, x: int) -> int:
        
        if x > 0:
            y = str(x)[::-1]
            y = int(y)
        else:
            x = abs(x)
            y = str(x)[::-1]
            y = '-' + y
            y = int(y)
        
        minx = -2**31  
        maxx = 2**31 - 1

        if y not in range(minx, maxx):
            return 0
        else:
            return y
