# c++
1. vector<int> nums;\
   nums.resize(10); //set zero
2. vector<int> nums;\
   nums.push_back(1); //add a element
3. nums.erase(v.begin()+1); //delete by index
4. 
5. vector<int> nums;\
   NumArray(vector<int>& nums) {\
   &nbsp; this->nums = nums; //use ->\
   }
6. struct ListNode {\
 &nbsp; int val;\
 &nbsp; ListNode *next;\
 &nbsp; ListNode() : val(0), next(nullptr) {}\
 &nbsp; ListNode(int x) : val(x), next(nullptr) {}\
 &nbsp; ListNode(int x, ListNode *next) : val(x), next(next) {}\
};
7. ListNode* dummy = new ListNode(-1), *p = dummy;

# leetcode
10/25 题目304\
前缀和

10/26 题目21\
双指针

10/27 题目86 23\
不要设计太复杂，先设计两个链表操作后最后合并


