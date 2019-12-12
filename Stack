class MinStack(object):

    def __init__(self):
        """
        initialize your data structure here.
        """
        self.items=[]
        
        
    def push(self, x):
        """
        :type x: int
        :rtype: None
        """
        self.items.append(x)

    def pop(self):
        """
        :rtype: None
        """
        return self.items.pop()
        

    def top(self):
        """
        :rtype: int
        """
        return self.items[len(self.items)-1]
        
        

    def getMin(self):
        """
        :rtype: int
        """
        return min(self.items)


# Your MinStack object will be instantiated and called as such:
obj = MinStack()
obj.push(12)
obj.push(13)
obj.push(14)
obj.pop()
param_3 = obj.top()
param_4 = obj.getMin()
