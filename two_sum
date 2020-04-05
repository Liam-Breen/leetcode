 
class Solution(object):
    def twoSum(self, nums, target):
        """
        :type nums: List[int]
        :type target: int
        :rtype: List[int]
        """
        count1 = 0

        for i in nums:
            count2 = 0
            for j in nums:

                if count2 != count1:
                    if i + j == target:
                        return [count1, count2]
                    else:
                        count2 += 1
                else:
                    count2 += 1
            count1 += 1
