# UI窗口  
## 简介  
UI窗口是基岩版所特有的交互机制，服务器可以向客户端发送简单窗口(多选窗口)、对话框(双选窗口)、高级窗口(自定义窗口)来让玩家进行操作，是服务器插件开发中的重要内容。  
BlocklyNukkit提供了一套友好的机制来让您快速地构建窗口，本节将带您学习使用它们。  

## 窗口构建器  
(原) 创建一个自定义窗口  
```javascript
// javascript  
let win = window.getCustomWindowBuilder('自定义窗口标题'); //创建窗口  
win.buildInput('输入框', '输入框提示', '输入框默认文本');  
win.buildDropdown('下拉框', '项目1;项目2;项目3');  
win.buildToggle('一个开关');  
win.showToPlayer(player, F(function (event){  
    // more code...  
}));// 发送窗口  
```  
(新) 扁平化创建一个自定义窗口  
```javascript
// javascript  
let win = window.getCustomWindowBuilder('自定义窗口标题')  
    .input('输入框', '输入框提示', '输入框默认文本')  
    .dropdown('下拉框', '项目1;项目2;项目3')  
    .toggle('一个开关')  
    .show(player, F(function (event){  
        // more code...  
    }));  
```  
参考  
```
SimpleWindowBuilder  
-  buildButton(String text,String img)  
-  button(String text,String img)  
-  button(String text)  
-  setAction(String actionFunctionName/F function)  
-  action(String actionFunctionName/F function)  
-  setTitle(String title)  
-  title(String title)  
-  setContext(String context)  
-  context(String context)  
-  showToPlayer(Player p)  
-  showToPlayer(Player p,boolean acceptClose)  
-  showToPlayer(Player p,String callbackFunctionName/F function)  
-  showToPlayer(Player p,String callbackFunctionName/F function,boolean acceptClose)  
-  show(Player p)  
-  show(Player p,boolean accpetClose)  
-  show(Player p,String callbackFunctionName/F function)  
-  show(Player p,String callbackFunctionName/F function,boolean acceptClose)  
ModalWindowBuilder  
-  setTitle(String title)  
-  title(String title)  
-  setContext(String context)  
-  context(String context)  
-  setButton1(String text)  
-  setButton2(String text)  
-  button1(String text)  
-  button2(String text)  
-  setAction(String callbackFunctionName/F function)  
-  action(String callbackFunctionName/F function)  
-  showToPlayer(Player p)  
-  showToPlayer(Player p,boolean acceptClose)  
-  showToPlayer(Player p,String callbackFunctionName/F function)  
-  showToPlayer(Player p,String callbackFunctionName/F function,boolean acceptClose)  
-  show(Player p)  
-  show(Player p,boolean accpetClose)  
-  show(Player p,String callbackFunctionName/F function)  
-  show(Player p,String callbackFunctionName/F function,boolean acceptClose)  
CustomWindowBuilder  
-  setTitle(String title)  
-  showToPlayer(Player p)  
-  showToPlayer(Player p,boolean acceptClose)  
-  showToPlayer(Player p,String callbackFunctionName/F function)  
-  show(Player p)  
-  show(Player p,boolean accpetClose)  
-  show(Player p,String callbackFunctionName/F function)  
-  show(Player p,String callbackFunctionName/F function,boolean acceptClose)  
-  showToPlayer(Player p,String callbackFunctionName/F function,boolean acceptClose)  
-  showAsSetting(Player p, String callbackFunctionName/F function)  
-  showAsSetting(Player p, String imageURL, String callbackFunctionName/F function)  
-  buildLabel(String text)  
-  label(String text)  
-  buildInput(String title,String placeholder)  
-  input(String title,String placeholder)  
-  buildInput(String title,String placeholder,String defaulttext)  
-  input(String title,String placeholder,String defaulttext)  
-  buildToggle(String title)  
-  toggle(String title)  
-  buildToggle(String title,boolean open)  
-  toggle(String title,boolean open)  
-  buildDropdown(String title,String inner)  
-  dropdown(String title,String inner)  
-  buildDropdown(String title,String inner,int index)  
-  dropdown(String title,String inner,int index)  
-  buildSlider(String title,double min,double max,int step,double defaultvalue)  
-  slider(String title,double min,double max,int step,double defaultvalue)  
-  buildSlider(String title,double min,double max,int step)  
-  slider(String title,double min,double max,int step)  
-  buildSlider(String title,double min,double max)  
-  slider(String title,double min,double max)  
-  buildStepSlider(String title,String options)  
-  stepSlider(String title,String options)  
-  stepslider(String title,String options)  
-  buildStepSlider(String title,String options,int index)  
-  stepSlider(String title,String options,int index)  
-  stepslider(String title,String options,int index)  
-  setAction(String callbackFunctionName/F function)  
-  action(String callbackFunctionName/F function)  
```  
