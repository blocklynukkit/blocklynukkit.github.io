# 高级窗口  
代码  
----  

~~~~python  
def test(sender, args):  
    test = window.getCustomWindowBuilder("Test") #创建一个高级窗口  
    test.buildLabel("Label") #创建一个标签,参数1标题  
    test.buildInput("Input", "Input") #创建一个输入框,参数1标题,参数2提示  
    test.buildToggle("Toggle") #创建一个开关,参数1标题  
    test.buildDropdown("Dropdown", "ABCD") #创建一个下拉框,参数1标题,参数2元素列表,用分号隔开  
    test.buildSlider("Slider", 0.0, 100.0, 1.0) #创建一个滑块条,参数1标题,参数2最小的值,参数3最大的值,参数4刻度  
    test.buildStepSlider("Slider", "ABCDEF") #创建一个 步骤滑块条,参数1标题,参数2元素列表,用分号隔开  
    test.showToPlayer(sender, "Call")  
def Call(e):  
    #获取元素,参数2元素位置,从0开始,参数3元素类型  
    logger.info(window.getEventCustomVar(e, 1, "input"))  
    logger.info(window.getEventCustomVar(e, 2, "toggle"))  
    logger.info(window.getEventCustomVar(e, 3, "dropdown"))  
    logger.info(window.getEventCustomVar(e, 4, "slider"))  
    logger.info(window.getEventCustomVar(e, 5, "stepslider"))  
~~~~