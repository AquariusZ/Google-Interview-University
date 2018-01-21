* 树----笔记 &amp; 背景
    - [ ] [系列：基本树(视频)](https://www.coursera.org/learn/data-structures-optimizing-performance/lecture/ovovP/core-trees)
    - [ ] [系列：树(视频)](https://www.coursera.org/learn/data-structures/lecture/95qda/trees)
    * 基本的树形结构
    * 遍历
    * 操作算法
    * BFS(广度优先检索，breadth-first search)
        * [MIT(视频)](https://www.youtube.com/watch?v=s-CYnVz-uh4&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=13)
        * 层序遍历（使用队列的 BFS 算法）
        * 时间复杂度： O(n)
        * 空间复杂度：
            * 最好情况： O(1)
            * 最坏情况：O(n/2)=O(n)
    * DFS(深度优先检索，depth-first search)
        * [MIT(视频)]()
        * 笔记：
            * 时间复杂度：O(n)
            * 空间复杂度：
                * 最好情况：O(log n) - 树的平均高度
                * 最坏情况：O(n)
        * 中序遍历（DFS：左、节点本身、右）
        * 后序遍历（DFS：左、右、节点本身）
        * 先序遍历（DFS：节点本身、左、右）
* 二叉查找树(Binary search trees)：BSTs
    - [ ] [二叉查找树概览(视频)](https://www.youtube.com/watch?v=x6At0nzX92o&index=1&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6)
    - [ ] [系列(视频)](https://www.coursera.org/learn/data-structures-optimizing-performance/lecture/p82sw/core-introduction-to-binary-search-trees)
        * 从符号表开始到 BST 程序
    - [ ] [介绍(视频)]()
    - [ ] [MIT(视频)]()
    * C/C++:
        - [ ] [二叉查找树 —— 在 C/C++ 中实现(视频)](https://www.youtube.com/watch?v=COZK7NATh4k&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=28)
        - [ ] [BST 的实现 —— 在堆栈和堆中的内存分配(视频)](https://www.youtube.com/watch?v=hWokyBoo0aI&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=29)
        - [ ] [在二叉查找树中找到最小和最大的元素(视频)](https://www.youtube.com/watch?v=Ut90klNN264&index=30&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
        - [ ] [寻找二叉树的高度(视频)](https://www.youtube.com/watch?v=_pnqMz5nrRs&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=31)
        - [ ] [二叉树的遍历 —— 广度优先和深度优先策略(视频)](https://www.youtube.com/watch?v=9RHO6jU--GU&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=32)
        - [ ] [二叉树：层序遍历(视频)](https://www.youtube.com/watch?v=86g8jAQug04&index=33&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
        - [ ] [二叉树的遍历：先序、中序、后序(视频)](https://www.youtube.com/watch?v=gm8DUJJhmY4&index=34&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
        - [ ] [判断一棵二叉树是否为二叉查找树(视频)](https://www.youtube.com/watch?v=yEwSGhSsT0U&index=35&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
        - [ ] [从二叉查找树中删除一个节点(视频)](https://www.youtube.com/watch?v=gcULXE7ViZw&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=36)
        - [ ] [二叉查找树中序遍历的后继者(视频)](https://www.youtube.com/watch?v=5cPbNCrdotA&index=37&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
    - [ ] 实现：
        - [ ] insert // 往树上插值
        - [ ] get_node_count // 查找树上的节点数
        - [ ] print_values // 从小到大打印树中节点的值
        - [ ] delete_tree
        - [ ] is_in_tree // 如果值存在于树中则返回 true
        - [ ] get_height // 返回节点所在的高度（如果只有一个节点，那么高度则为1）
        - [ ] get_min // 返回树上的最小值
        - [ ] get_max // 返回树上的最大值
        - [ ] is_binary_search_tree
        - [ ] delete_value
        - [ ] get_successor // 返回给定值的后继者，若没有则返回-1
