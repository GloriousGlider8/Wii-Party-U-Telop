Use the telop.max file to get the text model then apply materials and render using render.blend!
MAKE SURE YOU PUT "lg" after the text and DON'T REMOVE IT UNTIL YOU'VE FINISHED UV MAPPING

For getting each material on each part quickly, do the following:
- Apply the TextSides material as the first and default one on the text object.
- Add both other materials.
- Go into a side Orthographic projection view.
- Enable the X-Ray mode and go into face select mode.
- Drag a thin line at the top layer to select all the top faces then apply the text material.
- Drag a thin line at the bottom layer to select all the top faces then apply the outline material.
- You can then go into UV Editing mode, select the text faces (by using the select by material option),
  then go into a top Orthographic projection view.
- Press U and then Project from View (Bounds)
- Do the same with the TextSides Faces

Now, open the image in GIMP, you may need to adjust contrast and brightness using CTRL+A then go to Colours (top bar) then Brightness-Contrast.
For a gold text, I used:
Brightness 55
Contrast 38

OK so for shadows go over to shadows in gimp.docx