# my_journey
this is all about my daily coding and digital journal.
date 08.02.2026
//time 9 to 10pm
learned about recursion and linkedlist basics

sample code for merge 2 sorted LL
  class solution{
  public:
    ListNode* Msll(ListNode* l1,ListNode* l2);
      if (l1->val==nullptr){return l2;}
      if (l2->val==nullptr){return l1;}
      // very base caseeee/////

      if (l1->val<l2->val)
      {
        l1->val=Msll(l1->next,l2);
        return l1 
        //conditions with return/////
      }
      else
      {
        l2->val=Msll(l2->next,l1);
        return l2 
      }
      //////// 
      End of then day/////
  









  
  }
