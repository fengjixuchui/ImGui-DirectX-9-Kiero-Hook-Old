# ImGui-DirectX-9-Kiero-Hook
<h1>Setting up the solution</h1>
<ul>
  <li>Download and install <a href="https://www.microsoft.com/en-us/download/details.aspx?id=6812">DirectX SDK</a> and <a href="https://developer.microsoft.com/en-US/windows/downloads/windows-10-sdk">Windows SDK</a></li>
  <li>Open the solution on Visual Studio and open the project Properties</li>
  <li>Go to VC++ Directories -> Include Directories. Click on 'Edit' and select the Include folder <br/>located on your DirectX SDK installation path. It is generally this one: <br/>%programfiles(x86)%\Microsoft DirectX SDK (June 2010)\Include\
  <li>Now go to VC++ Directories -> Library Directories. Click on 'Edit' and select the library folder <br/> located on your DirectX SDK installation path. It is generally this one: <br/>%programfiles(x86)%\Microsoft DirectX SDK (June 2010)\Lib\x86\</li>
  <li><b>Done!</b></li>
  <li><b>OBS: The macro WINDOW_NAME is defined on the file "includes.h"</b></li>
</ul>
