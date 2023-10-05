class Solution {
public:
    bool check(vector<int>& nums) {
        int big{0};
        int n=nums.size();
        for(int i=0;i<n-1;i++)
        {
            if(nums.at(i)>nums.at(i+1))
            {
                big++;
            }
        }
        if(nums.at(0)<nums.at(n-1))
        big++;
        if(big>=2)
        return false;
        else
        return true;
    }
};
