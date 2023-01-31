# competitive-P
class Solution:
    def targetIndices(self, nums: List[int], target: int) -> List[int]:
        nums.sort()
        answer=[]
        for num in range(len(nums)):
            if (nums[num]==target):
                answer.append(num)
        return answer
