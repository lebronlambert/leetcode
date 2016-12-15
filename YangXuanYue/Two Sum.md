Solution

Use two std::unordered_map to store the visited number and their positions, just scan and check.

Code

class Solution {
public:
    vector<int> twoSum(vector<int>& nums, int target) {
        unordered_map<int, bool> vis;
        unordered_map<int, int> pos;
        vector<int> ans;
        for (int i(0); i < nums.size(); ++i) {
            if (vis[target - nums[i]]) {
                ans.push_back(pos[target - nums[i]]);
                ans.push_back(i);
                break;
            }
            vis[nums[i]] = true;
            pos[nums[i]] = i;
        }
        return ans;
    }
};
