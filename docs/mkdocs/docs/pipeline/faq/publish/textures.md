# **Publishing a new version for textures files**

1. Open **Maya 2017** using **{{ project.name }} Launcher**

    ![{{ project.name }} Launcher](../../../img/shading_publish_0.png?style=centerme)

    ***

2. Launch **{{ project.name }} Pipelinizer** tool

    > {{ project.name }} Pipelinizer Button in {{ project.name }} Shelf
    ![{{ project.name }} Pipelinizer](../../../img/shading_publish_1.png?style=centerme)

    ***

3. Open {{ project.name }} Publisher by pressing **>PUBLISH NEW VERSION<** button located in the bottom right corner of 
**{{ project.name }} Pipelinizer**

    > Solstice Pipelinizer Button in Solstice Shelf
    ![Solstice Pipelinizer](../../../img/shading_publish_7.png?style=centerme)
    
    !!! warning
        When **Solstice Publisher** is launched, it checks for the latest version by connecting to **Artella server**
        This **can take time**, so be **patient**. You will see the following dialog in the center of your Maya viewport.
        
        ![Solstice Working Button](../../../img/solstice_publisher_wait.png?style=centerme)
        
    ***

4. Make sure **TEXTURES** checkbox is checked.
    
    !!! info "IMPORTANT"
        You will notice that when you check **TEXTURES** checkbox, **MODEL**  and **SHADING** checkboxes are 
        automatically selected. This is complete normal. This means that each time you publish textures files a new 
        model file and shading will be published.
        
        This is happening because when textures are published, Solstice Publisher automatically updates shader 
        textures with the latest published textures version files.
        
    > Publishing Textures
    ![Solstice Pipelinizer](../../../img/textures_publish_0.png?style=centerme)
