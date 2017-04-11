# ram_modified

-- Refer

Recurrent Models of Visual Attention
http://papers.nips.cc/paper/5542-recurrent-models-of-visual-attention.pdf

-- Author

Juntae, Kim  |  jtkim@kaist.ac.kr

-- Require

'tensorflow rc 1.1.0-rc0'

-- Updated file

ram_modified.py

-- Description

This is modified version of https://github.com/jlindsey15/RAM

'Note that stop gradient issue was solved'

The critical issue in https://github.com/jlindsey15/RAM is that they cannot learn the parameters of location network.

In this version, they can learn using reinforcement learning stretegy 

However, the accuracy is just 94%. If anyone increase this, plz notice me the way how can increase.

Thx!
