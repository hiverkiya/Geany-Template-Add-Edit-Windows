## Geany Template Add/Edit Windows10

#### You can't Edit/Add Geany template files in Windows using File explorer because of [UAC](https://en.wikipedia.org/wiki/User_Account_Control)

Follow steps below to Add/Edit/Delete:-

1. Open Powershell in Elevated priviledges

![Powershell](https://github.com/hiverkiya/Geany-Template-Add-Edit-Windows-/blob/main/media/1.png)

2. Navigate to Geany Template files location using _cd_ command, If your Geany installation location is in 'Program Files (x86)' , type 
 `` cd p`` then press tab couple of times until you see your directory and press ``Enter``
  Pressing ``Tab`` Key will autocomplete the current File/Folder name.
![Powershell Navigation](https://github.com/hiverkiya/Geany-Template-Add-Edit-Windows-/blob/main/media/geany.gif)

3. Creating/Editing/Deleting template files
  To Create new template file use ``New-Item filename.extension`` Format. There is ``-`` (minus) symbol between _New_ and _Item_
 
 ![Creating Files](https://github.com/hiverkiya/Geany-Template-Add-Edit-Windows-/blob/main/media/Creating%20Files.PNG)
 
 Like I have created mine using `New-Item cp.cpp` 
 
 ![Creating Template](https://github.com/hiverkiya/Geany-Template-Add-Edit-Windows-/blob/main/media/Creating%20template.PNG)
 
 To delete use
 `del filename`
You can press `Tab` to autocomplete
 ![Deleting File](https://github.com/hiverkiya/Geany-Template-Add-Edit-Windows-/blob/main/media/delete.gif)

4. Editing File
  Notice the length of file created is 0, means it doesn't contain anything _yet_.
  Type first few letter of file and press `Tab` and `Enter`. Pressing `Tab` key will autocomplete the File/Folder name matching.  
  Your file will be opened in Default Editor/IDE you've specified
  ![Opening File](https://github.com/hiverkiya/Geany-Template-Add-Edit-Windows-/blob/main/media/comp.gif)

5. Editing Template
 Follow ![Template Customization Guide](https://www.geany.org/manual/current/index.html#customizing-templates)
 _Don't be scared, its just few paragraphs you need to read to customize_
For a basic template like mine you can just add basics
![Template Format](https://github.com/hiverkiya/Geany-Template-Add-Edit-Windows-/blob/main/media/template.PNG)
Which will be rendered like this in Geany
![geanyTemplate](https://github.com/hiverkiya/Geany-Template-Add-Edit-Windows-/blob/main/media/geanyTemplate.PNG)

6. Creating New File from Template
   Click on dropdown button to right of `New` Button or Goto ``File -> New (with Template)`` and click on your custom template
   ![](https://github.com/hiverkiya/Geany-Template-Add-Edit-Windows-/blob/main/media/newDropDown.png)
   ![](https://github.com/hiverkiya/Geany-Template-Add-Edit-Windows-/blob/main/media/geanyNewTemplate.png)

Voila!
![](https://github.com/hiverkiya/Geany-Template-Add-Edit-Windows-/blob/main/media/open.gif)

   
