---
layout: post
title: Randomization on quick sort
meta: MIT lecture
---

"Every piece of study is somehow related to art" -- we encounter that in case of computer science when we see some of elegant algorithm design by human brain. Quicksort is an apt example of human imagination which leads to a exquisite solution technique of a common problem.<br>
Quicksort belongs to the 'divide and conquer' paradigm and it sorts in place. If we apply some technique to tune it, quicksort is one of the very few practical sorting mechanism available till date.<br>
Picking up pivot in a constant manner every time in partition method will reduce the hamper complexity of quick sort. we will get O(n^2) worst-case time complexity. This will significantly increase this by selecting the pivot element randomly.<br>

