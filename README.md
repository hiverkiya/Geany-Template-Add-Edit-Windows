## Geany Template Add/Edit Windows10

##### Inspiration for this guide is [Errichto](https://www.youtube.com/channel/UCBr_Fu6q9iHYQCh13jmpbrg)

You can setup [Geany](https://www.geany.org/) for _Competitive Programming_ using [Linux setup for Competitive Programming (with Geany)](https://youtu.be/ePZEkbbf3fc)

To setup [Geany](https://www.geany.org/) Templates in Windows_10 follow steps below :-

#### You can't Edit/Add Geany template files in Windows using File explorer because of [UAC](https://en.wikipedia.org/wiki/User_Account_Control)

Follow the steps below to Add/Edit/Delete:-

1. Open Powershell in Elevated privileges

![Powershell](https://github.com/hiverkiya/Geany-Template-Add-Edit-Windows-/blob/main/media/1.png)

2. Navigate to the Geany Template files location using the _cd_ command
   
   If your Geany installation location is in 'Program Files (x86)', type 
   `` cd p`` then press the tab couple of times until you see your directory and press ``Enter ``
   Pressing the ``Tab`` Key will autocomplete the current File/Folder name.

  ![Powershell Navigation](https://github.com/hiverkiya/Geany-Template-Add-Edit-Windows-/blob/main/media/geany.gif)

3. Creating/Editing/Deleting template files
  
  To Create a new template file, use ``New-Item filename.extension`` Format. There is ``-`` (minus) symbol between _New_ and _Item_
 
  ![Creating Files](https://github.com/hiverkiya/Geany-Template-Add-Edit-Windows-/blob/main/media/Creating%20Files.PNG)
 
  Like I have created mine using `New-Item cp. cpp` 
 
  ![Creating Template](https://github.com/hiverkiya/Geany-Template-Add-Edit-Windows-/blob/main/media/Creating%20template.PNG)
 
  To delete use
  `del filename`
  You can press `Tab` to autocomplete
 
 ![Deleting File](https://github.com/hiverkiya/Geany-Template-Add-Edit-Windows-/blob/main/media/delete.gif)

4. Editing File
  
  Notice the length of the file created is 0, which means it doesn't contain anything _yet_.
  Type the first few letters of the file and press `Tab` and `Enter` Pressing the `Tab` key will autocomplete the File/Folder name matching.  
  Your file will be opened in Default Editor/IDE you've specified.
  
  ![Opening File](https://github.com/hiverkiya/Geany-Template-Add-Edit-Windows-/blob/main/media/comp.gif)

5. Editing Template
   
   Follow [Template Customization Guide](https://www.geany.org/manual/current/index.html#customizing-templates)
   
   _Don't be scared; it's just a few paragraphs you need to read to customize_
   
   You can add basics like these for a basic template like mine.
   
   ![Template Format](https://github.com/hiverkiya/Geany-Template-Add-Edit-Windows-/blob/main/media/template.PNG)
   
   Which will be rendered like this in Geany
   
   ![geanyTemplate](https://github.com/hiverkiya/Geany-Template-Add-Edit-Windows-/blob/main/media/geanyTemplate.PNG)

6. Creating New File from the Template
   
   Click on the dropdown button to the right of the `New` Button or Goto ``File -> New (with Template)`` and click on your custom template.
   
   ![newDropDown](https://github.com/hiverkiya/Geany-Template-Add-Edit-Windows-/blob/main/media/newDropDown.png)
   
   ![geanyNewtemplate](https://github.com/hiverkiya/Geany-Template-Add-Edit-Windows-/blob/main/media/geanyNewTemplate.png)

   Voila! Make sure to save your file either from the `File` Menu option or `CTRL + S` and give your file a _beautiful name_
   
   ![open](https://github.com/hiverkiya/Geany-Template-Add-Edit-Windows-/blob/main/media/open.gif)

   
