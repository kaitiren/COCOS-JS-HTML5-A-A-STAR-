COCOS-JS HTML5 (A-Star)
=======================

A * algorithm, A * (A-Star) algorithm is a static road network to solve the shortest most effective method. Estimated value closer to the actual value, the valuation function get better.


# Example

This sets up a map matrix, 0 null, 1 wall, 2 grass,Such as:
        
        ```
        var mapMatrix = [
                [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
                [0, 2, 0, 0, 1, 1, 0, 0, 2, 2, 0, 1, 0, 0, 1],
                [0, 2, 0, 0, 1, 0, 0, 0, 2, 0, 0, 1, 0, 1, 0],
                [0, 2, 2, 0, 1, 1, 1, 0, 0, 0, 2, 2, 2, 2, 0],
                [0, 0, 0, 1, 1, 0, 0, 0, 2, 2, 2, 0, 0, 0, 0],
                [0, 0, 0, 0, 0, 0, 0, 0, 2, 0, 0, 0, 0, 0, 0],
                [0, 0, 1, 1, 1, 1, 0, 0, 2, 0, 0, 0, 0, 0, 0],
                [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 2, 0, 0],
                [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 2, 2, 0, 0],
                [1, 1, 1, 1, 0, 0, 0, 0, 1, 0, 2, 2, 0, 0, 0],
                [0, 0, 0, 1, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0],
                [0, 0, 0, 1, 0, 0, 0, 0, 1, 1, 1, 1, 1, 0, 0],
                [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0],
                [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0],
                [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]
             ];
        ```
        
The second A-star search path, Such as:
       ```
       aStarManager.init(mapMatrix, startPoint, endPoint, [1, 2]);
       path = aStarManager.getPath();
       ```
       
Lincense
========
Copyright (c) 2013 kaitiren. All rights reserved.


