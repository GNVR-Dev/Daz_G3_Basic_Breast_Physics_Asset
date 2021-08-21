# Daz_G3_Basic_Breast_Physics_Asset
Basic G3 female breast physics asset

Make sure you have at least one character named Genesis3Female in your project

Download and extract the UpL8_G3_PhysicsAsset.uasset

Copy and paste the UpL8_G3_PhysicsAsset.uasset into your Unreal Engine Project's DazToUnreal Animation Folder

<img width="1346" alt="AnimationFolder" src="https://user-images.githubusercontent.com/38672299/130334842-627a4946-1e4e-4494-9b94-5d7dcc236402.png">

Open your character mesh. In the Aset Details Panel scroll down to Physics and change the Physics Asset to the  UpL8_G3_PhysicsAsset.uasset

<img width="1920" alt="MeshWindow" src="https://user-images.githubusercontent.com/38672299/130335035-06a8dd19-16bc-4567-b18b-e3f02e407ced.png">

At the bottom there is a notification that there is a post process animation running. Click edit.

<img width="1920" alt="Edit_Post_Process_Animation" src="https://user-images.githubusercontent.com/38672299/130334641-9c31afcf-2954-418d-a520-8fef03719773.png">

Keep in mind the Post Process Animation is part of the DaztoUnreal plugin. Any changes made here will effect all projects using the plugin.
In the Post Process Animation simply add a Rigid Body node here. Compile - and try Playing the level again.

<img width="1920" alt="Add_Rigid_Body" src="https://user-images.githubusercontent.com/38672299/130334701-42d52890-e45e-4380-948c-8a0af2e3024f.png">

If you don't want to mess with the Plugin Post Process Animation:
Drag a copy into your projects DazToUnreal animation folder.
To find where it is located click on the Browse button

<img width="1920" alt="Browse" src="https://user-images.githubusercontent.com/38672299/130334714-e38de7e6-c7f6-4b8c-b619-5742ef779a54.png">

Make sure the Source Panel is open in the lower left hand side, drag the Post Process Animation to the DazToUnreal Animation folder. Click Copy Here

<img width="1920" alt="Copy_Here" src="https://user-images.githubusercontent.com/38672299/130334732-8bfcea96-333d-4df6-b34b-96457fb38bbb.png">

Now you just need to add the Rigid body node to your copy of the Post Process Animation and set your character mesh to use this one instead.
To do so open you character mesh scroll down to Skeletal Mesh - Post Process Anim Blueprint and set it to the one located in your Animation folder.

<img width="1920" alt="Set_New_Post_Process" src="https://user-images.githubusercontent.com/38672299/130334760-e4db2e90-e543-43fa-b6bb-ae341acf3909.png">
