# Houdini Procedural Worflows
A huge part of what has made the SimFirefighter project run smoothly has been the thoughtful pre-development work that allowed us to streamline asset creation through the use of procedural tools—in this case, Houdini procedurals.

![image](https://github.com/user-attachments/assets/f932b113-7f1f-4e67-b470-7115f0ed226f)
Houdini, with its node-based workflows, is the ultimate IDE for geometry construction. With its rich set of features, procedurally constructing geometry assets becomes a breeze. This is all integrated through the Houdini Engine plugin, allowing our team to develop systematic workflows that manipulate geometric constructions through a nested backend system. 

### Constructing Digital Assets
![intro_sessiondiagram](https://github.com/user-attachments/assets/ace91e6c-c0be-4b97-9b7e-03882d32700b)
It works by building a digital asset, a geometry file that exposes editable parameters which can be piped back through the pipeline to create live updates on the fly. In our case, this has been extremely handy for constructing the dynamic elements of our firefighting map. 
We aimed to build systems that enhance the gameplay experience, and this would be extremely challenging without procedural generation. It allows us to construct the forest, foliage, and material placements efficiently, using a procedural layering toolkit. 
Currently, we’ve begun placing the foliage and applying various mask layers to capture the experience of a more immersive map. What’s neat about this workflow is that all the construction elements flow through the pipeline and are highly modular, making it easy to implement new changes and giving us flexibility when edits are needed.

In our case, we have begun placing the folliage and various mask layers to capture the expereince of a more emmersive map. What is neat about this workflow, all the construction elements flow through the pipeline
and are highly steppable for building new changes that give us flexibilities when edits are needed.

### The Map
![image](https://github.com/user-attachments/assets/4fc5a5e3-8902-4251-bbb1-02528d442b9f)
In our most recent iteration of the project, we’ve taken steps to design the map around fire combat strategy, placing two water towers and visual feedback elements into the gameplay experience.
With these tools, we can quickly adapt the framework to suit user needs, making small tweaks in visual production. In this case, we’ve chosen to use two water towers and a visual path that cuts through the map, highlighting the fastest routes between them for helicopter refills.
