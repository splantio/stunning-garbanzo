# stunning-garbanzo
Excuse the name, I was lazy and let GitHub name it for me.

A repo for a small text-to-speech Windows form application that will allow a user to save text as a .wav file for later listening.

So I've seen a couple text to mp3 apps out there but they're kinda costly. Basically I want someone to read my (online) textbooks and notes to me on the long drives from where I live to my hometown when I visit my folks, and when I'm cooking or otherwise away from a computer or tablet. I figured it could be a fun little project on the side as well.

This app uses [this](https://msdn.microsoft.com/en-us/library/ms586885(v=vs.110).aspx) reference as its messiah, since I'd be far and away lost without it. Credit to the Microsoft Developer Network.

# Notes for forkers
In order for the solution to open in Visual Studio without errors, you'll need to have the 

[Microsoft Visual Studio **2013** Installer Projects extension](https://visualstudiogallery.msdn.microsoft.com/9abe329c-9bba-44a1-be59-0fbf6151054d/file/130817/3/VSI_bundle.exe)

or the

[Microsoft Visual Studio **2015** Installer Projects extension](https://visualstudiogallery.msdn.microsoft.com/f1cc3f3e-c300-40a7-8797-c509fb8933b9/file/171165/2/VSI_bundle.exe)

and you may have to reinstall the iTextSharp package (Project > Manage NuGet Packages)

License
=======
   Copyright 2015 Spencer Plant, Wilson Quon

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

# The Future
Perhaps we'll try to work in functionality such that someone could take a picture of physical notes, and then provide that image or images as the text source.
