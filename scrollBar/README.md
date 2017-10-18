
##Chapter1: 关于CSS3自定义滚动条样式
 
前言：
    webkit支持拥有overflow属性的区域，列表框，下拉菜单，textarea的滚动条自定义样式，
    所以用处还是挺大的。当然，兼容所有浏览器的滚动条样式目前是不存在的。
滚动条的组成部分：
    ::-webkit-scrollbar 滚动条整体部分
    ::-webkit-scrollbar-thumb  滚动条里面的小方块，能向上向下移动（或往左往右移动，取决于是垂直滚动条还是水平滚动条）
    ::-webkit-scrollbar-track  滚动条的轨道（里面装有Thumb）
    ::-webkit-scrollbar-button 滚动条的轨道的两端按钮，允许通过点击微调小方块的位置。
    ::-webkit-scrollbar-track-piece 内层轨道，滚动条中间部分（除去）
    ::-webkit-scrollbar-corner 边角，即两个滚动条的交汇处
    ::-webkit-resizer 两个滚动条的交汇处上用于通过拖动调整元素大小的小控件