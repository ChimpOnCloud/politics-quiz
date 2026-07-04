整理到docs/data时，请阅读本文件。
problem_xxx中，包含content.txt。里面包含了题目的题干、选项和答案。请你首先整理好格式，然后提取到docs/data的json中。
部分题目会有problem.png，对应docs/data/scientific/physics_physics_xxx_problem.png，请在题目显示时包含这张图。
部分题目会有answer.png，对应docs/data/scientific/physics_physics_xxx_answer.png，请在显示答案时包含这张图。
部分题目的选项可能会有图片，对应docs/data/scientific/physics_physics_xxx_option_yyy.png，请在题目显示时在对应选项中包含这张图。
每道题在docs/data中的problems.json中组织一项；同时维护两个png以及一个answer.txt。
可能会有一些题目没有图片，这种情况请忽略图片的处理。