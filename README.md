# Daz_G3_Basic_Breast_Physics_Asset
Basic G3 female breast physics asset

Make sure you have at least one character named Genesis3Female in your project

Download and extract the UpL8_G3_PhysicsAsset.uasset

Copy and paste the UpL8_G3_PhysicsAsset.uasset into your Unreal Engine Project's DazToUnreal Animation Folder

<img width="1346" alt="AnimationFolder" src="https://user-images.githubusercontent.com/38672299/130334842-627a4946-1e4e-4494-9b94-5d7dcc236402.png">

Open your character mesh. In the Aset Details Panel scroll down to Physics and change the Physics Asset to the  UpL8_G3_PhysicsAsset.uasset

<img width="971" alt="G3_Mesh_Window" src="https://user-images.githubusercontent.com/38672299/130335301-f3d582f2-0c84-4a55-8209-79dd2614ee76.png">

At the bottom there is a notification that there is a post process animation running. Click edit.

<img width="960" alt="G3_Edit_Post_Process_Animation" src="https://user-images.githubusercontent.com/38672299/130335317-c8a9b81b-fb4f-4f33-9f8c-f37396daa963.png">

Keep in mind the Post Process Animation is part of the DaztoUnreal plugin. Any changes made here will effect all projects using the plugin.
In the Post Process Animation simply add a Rigid Body node here. Compile - and try Playing the level again.

<img width="1920" alt="G3_Add_Rigid_Body" src="https://user-images.githubusercontent.com/38672299/130335390-b01174be-41b9-4ab6-ac1a-0971aae6567f.png">

If you don't want to mess with the Plugin Post Process Animation:
Drag a copy into your projects DazToUnreal animation folder.
To find where it is located click on the Browse button

<img width="971" alt="G3_Browse" src="https://user-images.githubusercontent.com/38672299/130335399-a57706be-72e2-4638-ab86-d45efe8ad86f.png">

Make sure the Source Panel is open in the lower left hand side, drag the Post Process Animation to the DazToUnreal Animation folder. Click Copy Here

<img width="960" alt="G3_Edit_Post_Process_Animation" src="https://user-images.githubusercontent.com/38672299/130335408-82d18ec4-3d44-43a3-822e-17ba4bee074f.png">

Now you just need to add the Rigid body node to your copy of the Post Process Animation and set your character mesh to use this one instead.
To do so open you character mesh scroll down to Skeletal Mesh - Post Process Anim Blueprint and set it to the one located in your Animation folder.

<img width="1920" alt="G8_Set_New_Post_Process" src="https://user-images.githubusercontent.com/38672299/130335463-7f920de8-3d84-4485-bc10-65e9df96525b.png">
