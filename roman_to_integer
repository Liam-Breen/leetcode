class Solution:
    def romanToInt(self, s: str) -> int:

        vals = {
            'I': 1,
            'V': 5,
            'X': 10,
            'L': 50,
            'C': 100,
            'D': 500,
            'M': 1000
        }
        
        num = 0
        
        if len(s) == 1:
            return vals[s]
        elif len(s) > 1:
            prevnum = ""
            for i in s[::-1]:
                # print(i)
                if i == "I" and (prevnum == "X" or prevnum == "V"):
                    num -= 1
                    print(1)
                elif i == "X" and (prevnum == "L" or prevnum == "C"):
                    num -= 10
                    print(2)
                elif i == "C" and (prevnum == "D" or prevnum == "M"):
                    num -= 100
                    print(3)
                else:
                    num += vals[i]
                    print(4)
                prevnum = i
                # print(prevnum)
                # print(num)
        else:
            print("shouldnt be here..")
            
        return num
