# FAQ

<!-- ## 插件90%的问题 , 都可以在配置文件中找到 -->

#### 为什么我是OP却无法破坏岛屿之外的方块?

- 在配置文件 "Admin" 项 给自己添加岛屿管理员

#### 地狱/末地有岛屿保护怎么办?

- 在配置文件关闭地狱/末地的保护

#### 为什么我删除了岛屿 , 但岛屿范围内的建筑都还在?

- 出于玩家误操作的的考虑 , 玩家执行删除岛屿操作后 , 仅会将其岛屿数据删除 , 并不会清空岛屿所在区域的方块

#### 插件自带菜单与其他菜单冲突了 , 怎么办 ?

- 将配置文件 "Menu" 项 修改为 0, 也可以在 **plugins \ SkyBlock \ plugins** 文件夹中删除 **menu.js**

#### 插件自带的聊天前缀与其他插件(例如称号插件)冲突了怎么办?

- 在 **plugins \ SkyBlock \ plugins** 文件夹中删除 **onChat.js**
