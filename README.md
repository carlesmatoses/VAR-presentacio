- Introduction (what when and why)
- summary
- related works and what they matter 
- technical setup
- capturing people
- situating people (mostly occlusion)
- results (problems and limitations and participants)
- they're conclusion
- our conclusion and opinion


# Introduction:
We are presenting the paper A Video-Texture Based Approach for Realistic Avatars. 

This paper explains what are the avatars, why its important to make them as real as posible and and some circumstances where they can be useful.

In applications that require collaboration is important to provide the multiple integrants of the task with all the body language that can help in real tasks. they link to other works like  (e.g (Latoschik et al., 2017; Bailenson et al., 2006; Waltemate et al., 2018; Roth et al., 2016)). In projects that require real world precission is important to avoid the proteus effect where users adapts themselfs to the avatar.

<!-- insert funny video of vrchat proving this -->

Other problem with this kind of scenarios is the requiriments to create highly realistic avatars. They require scanning people fo example, obtining all bones movement and realistic rendering techniques. this make them costly.

- Generating custom avatars 
- Attaching trackers to users
- All prespectives are not avalible all the time.
- Pretained IA models for tracking improvements

The choosen approach for solving this challenge is to capture images of the users and project them inside the environment providing "visual realism".

<!-- insert image -->

To archieve it they make use of a novel aproach for extracting the images from the real world with low cost system  and some occlusion techniques to place them in a 2D plane in the scene.

The novel aproach includes:
- Low-Cost technical system
- Not required generating real geometry models or IA models

## related work
Is important to mention that other works approach this problem too. They're solutions make use of multiple cameras, multiple kineckt devices for depth information, realsitic models for avatars and so one.  (Zhu et al., 2016), uses an aproaach really close to this one but it does not integrate a 2D plane for representing the extracted images in the enviorment.

# Low cost video texture approach
