class Solution:

    def findMedianSortedArrays(self, nums1: List[int], nums2: List[int]) -> float:

        median = 0.0
        nums = nums1 + nums2
        nums.sort()

        indx = len(nums) // 2

        if len(nums) % 2 != 0:
            return float(nums[indx])
        else:
            return (nums[indx] + nums[indx - 1]) / 2

        return median
