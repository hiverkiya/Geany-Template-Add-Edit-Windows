## Geany Template Add/Edit Windows10

#### You can't Edit/Add Geany template files in Windows using File explorer because of [UAC](https://en.wikipedia.org/wiki/User_Account_Control)

Follow steps below to Add/Edit:-

1. Open Powershell in Elevated priviledges

![Powershell](https://github.com/hiverkiya/Geany-Template-Add-Edit-Windows-/blob/main/1.png)

2. Navigate to Geany Template files location using _cd_ command, If your Geany installation location is in 'Program Files (x86)' , type 
 `` cd p`` then press tab couple of times until you see your directory and press ``Enter``
  Pressing ``Tab`` Key will autocomplete the current File/Folder name.
![Powershell Navigation](https://github.com/hiverkiya/Geany-Template-Add-Edit-Windows-/blob/main/geany.gif)

3. Creating/Editing template files
  To Create new template file use ``New-Item filename.extension`` Format. There is ``-`` (minus) symbol between _New_ and _Item_
 
 ![Creating Files](https://github.com/hiverkiya/Geany-Template-Add-Edit-Windows-/blob/main/Creating%20Files.PNG)
 
 Like I have created mine using `New-Item cp.cpp` 
 
 ![Creating Template](https://github.com/hiverkiya/Geany-Template-Add-Edit-Windows-/blob/main/Creating%20template.PNG)

4. Editing File
  Notice the length of file created is 0, means it doesn't contain anything _yet_.
  Type first few letter of file and press `Tab` and `Enter`
  Your file will be opened in Default Editor/IDE you've specified
  
