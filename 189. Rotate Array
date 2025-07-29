class Solution {
public:
    void rotate(vector<int>& nums, int k) {
       //method 1
       /* int i = 0;
        int j = nums.size() - 1 ;
        
        k = k % nums.size() ;
        while(k) {
           while(i != j) { 
           swap(nums[i],nums[j]) ;
           i ++ ;
            }
            i = 0; 
            j = nums.size() - 1 ;
            k -- ;
        } */

        // method 2 
        k = k % nums.size() ;
        int n = nums.size() ;
        reverse(nums,0,n-1) ;
        reverse(nums,0,k-1) ;
        reverse(nums,k,n-1) ;

    }
    private : void reverse(vector<int> &nums,int start,int end) {
        while(start < end) {
            swap(nums[start],nums[end]) ;
            start ++ ;
            end -- ;
        }
    }
};
