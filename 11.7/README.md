Release Notes
=============

http://helpx.adobe.com/flash-player/release-note/fp_117_air_37_release_notes.html

> Authoring for Flash Player 11.7
> -------------------------------
> 
> To use the new Flash Player, you will need to target SWF version 20 by passing in an extra compiler argument to the Flex compiler: `-swf-version=20`.
> 
> Authoring for AIR 3.7 Update to the AIR 3.7 namespace
> -------------------------------
> 
> You must update your application descriptor file to the 3.7 namespace in order to access the new AIR 3.7 APIs and behavior. If your application does not require the new AIR 3.7 APIs and behavior, you are not required to update the namespace. However, we recommend all users start using the AIR 3.7 namespace even if you are not yet taking advantage of the new 3.7 capabilities. To update the namespace, change the xmlns attribute in your application descriptor to: `<application xmlns="http://ns.adobe.com/air/application/3.7">`