# Blender-Node-Layout-Organizer

This is a work in progress Addon to help automatically organise node layouts based on the work of the [Node Arrange an Official Addon](https://github.com/blender/blender-addons/blob/master/node_arrange.py). I am currently working on it in my freetime to improve/change some of its functionality. As of now I have not changed much of the original code and have been researching solutions and features that I wish to implement.

## Features to be Implemented
- [ ] 1) Implement Rudimentary Sugiyama Layout 
- [ ] 2) Add alignment options
- [ ] 3) Make it compatible with groups/frames
- [ ] 4) Add group/frame options

## As of now these are the current possibile ways to arrange Nodes in Blender that I have found:

1. Manual Arrangement (My Original Layout)
<p align="center">
  <img src="https://user-images.githubusercontent.com/65004578/150722884-294689e4-e78d-474e-8c86-7851b0d5e3bf.png" width=75% height=75%>
</p>

2. [Node Arrange Official Addon](https://github.com/blender/blender-addons/blob/master/node_arrange.py) (After Hitting Arrange All Nodes)
<p align="center">
  <img src="https://user-images.githubusercontent.com/65004578/150722895-63f9e1b6-22ec-4265-a105-c873ac00f014.png" width=75% height=75%>
</p>


3. [3DSinghVFX Node Align a Community Addon](https://github.com/3DSinghVFX/align_nodes) (I hit shift+E on the group input node and selected the dependecies to the right)
<p align="center">
  <img src="https://user-images.githubusercontent.com/65004578/150722935-9228f256-45c7-4ffe-b764-6215ae38877a.png" width=75% height=75%>
</p>

4. [Node Wrangler an Official Addon](https://github.com/blender/blender-addons/blob/master/node_wrangler.py) (I hit the node align button. Its utility seems to be more in arranging all the nodes into either a single row or a column but it wont arrange for both.)
<p align="center">
  <img src="https://user-images.githubusercontent.com/65004578/151657179-7072e5fc-5ee8-4248-83bc-13d8c78b4f21.png" width=75% height=75%>
</p>

These are some sites I am using to research this:
1. https://llimllib.github.io/pymag-trees/
2. https://www.wikiwand.com/en/Layered_graph_drawing
3. https://mindfusion.eu/graph-layout.html
4. https://www.baeldung.com/cs/graph-auto-layout-algorithm
5. https://crinkles.io/writing/auto-graph-layout-algorithm
6. https://docs.yworks.com/yfiles-html/dguide/layout/layout-summary.html#layout_styles-hierarchical
7. https://docs.yworks.com/yfiles-html/dguide/layout/hierarchical_layout.html#hierarchical_layout-grouping
8. https://docs.yworks.com/yfiles-html/dguide/layout/layout-summary.html#_node_types_in_the_hierarchical_layout
9. https://github.com/subhero24/sugiyama/tree/master/src
10. https://www.youtube.com/playlist?list=PLubYOWSl9mIvxe_HwoSyT-oXgkOmB1u3V
11. https://github.com/bdcht/grandalf
