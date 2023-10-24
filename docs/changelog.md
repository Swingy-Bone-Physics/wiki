## Version 1.1

### Update instructions

* If you used a previous version, first install the new one by following the [updating instructions](./setup.md/#update).
* Once that's done, you will have to **clear any collider or chain that you previously created using the "Clear All" operators** and recreate them. **Do not use any other operator before doing this or it may lead to some issues!**

<div align="center">
<video controls>
  <source src="../Resources/Vids/V11Clear.mp4" type="video/mp4">
</video>
</div>

### Changes

* The armatures' movements in Object Mode will now contribute to the chains' simulation. Both pose mode and object mode transformations will be taken into account now.

* Multiple armature collision support. The chains will now collide with any collider, whether or not they're part of the same armature.

<figure markdown>
  ![Image](./Resources/Vids/V11InterColl.gif){ width="400" }
</figure>

* Better operators version to take multiple armatures into account.

* Added a link to the wiki in the addon tab in the preferences menu

## Version 1.0

### Changes

* Initial release

