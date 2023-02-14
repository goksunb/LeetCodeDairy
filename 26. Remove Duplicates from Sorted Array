class Solution {
public:
    int removeDuplicates(vector<int>& nums) {
        int duplicatesEncountered = 0;
        for (int i = 1; i < nums.size(); i++) {
            if (nums[i] == nums[i - 1]) duplicatesEncountered++;
            else nums[i - duplicatesEncountered] = nums[i]; 
        }
        
        return nums.size() - duplicatesEncountered;
    }
};
