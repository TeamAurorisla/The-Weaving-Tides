# 1.20.1-Forge-Temple-pack
这个模板仓库是给我自己开发整合包或服务器用的，当然如果你想懒省事，也可以使用它。

顺带一提，这个环境是基于 [PrismLaucher](https://prismlauncher.org/) 开发的，因为它有方便的模组补全功能。

## 使用方法
1. 点击此页面偏右上角的`Use this template`，创建一个新的仓库

2. 打开PrismLauncher的根目录，在`instances`文件夹下创建一个空文件夹

3. 克隆你的新仓库到这个空文件夹里

   > 如果你用的是GitHub Desktop，那么当你填写的克隆地址为新建的文件夹时，它会自动补全克隆地址
   >
   > 例如你选取的是`xxx/PrismLauncher/instances/1.20.1`，而你新建的仓库名叫`Temple`
   >
   > 那么最后你克隆到本地的仓库目录为`xxx/PrismLauncher/instances/1.20.1/Temple`
   >
   > 这个时候把后面的Temple删掉就可以了。
   >
   > 当然，你也可以直接选取instances文件夹，这样最后的克隆结果为：`xxx/PrismLauncher/instances/Temple`，也不用再新建一个文件夹了。

4. 打开启动器，选中对应实例后进入`编辑/Mod`页面

   > 由于每一次进入到这个页面后，PrismLauncher都会自动检测mods文件夹内存在且有效的模组文件，导致不匹配的模组元数据都会被其自动删除，所以你此时执行下面的第五步并没有效果
   >
   > 不过有一个解决方案：
   >
   > 进入此页面后保持不动，然后从Git图形端把被删除的`*.pw.toml`文件全部给恢复回来
   >
   > 恢复文件后启动器里就会爆出一大堆模组，这个时候再执行第五步就可以正常下载模组了

5. 点击`检查更新`按钮，跳过`.gitignore`的检测，待检查完成后下载Mod

6. 大功告成，现在可以开发你的整合包了！
