# power-of-4
class Solution:
    def isPowerOfFour(self, n: int) -> bool:
        p=0
        while True:
            if pow(4,p)==n:
                return True
            if pow(4,p)>n:
                    return False
            p+=1
