Med hjälp från https://www.youtube.com/watch?v=JHTcLVOcnQ4...

Har kört inom C:\Users\tosse\GitHub\
git clone https://github.com/juce-framework/JUCE.git

Öppnat
C:\Users\tosse\GitHub\JUCE\extras\Projucer\Builds\VisualStudio2019\Projucer.sln
--> Build solution (i debug mode)

Kört
C:\Users\tosse\GitHub\JUCE\extras\Projucer\Builds\VisualStudio2019\x64\Debug\App\Projucer.exe
--> File/Sign in --> Enable GPL Mode
--> File/Global Paths... --> "Path to JUCE", "JUCE Modules" där det klonades in.

Kört lokalt: 
    git init
På github.com: 
    New repository "HelloWorldWin"
    git remote add origin https://github.com/bustad/HelloWorldWin.git
    git branch -M main
    git push -u origin main

git checkout -b "Graphics-Update"
git push --set-upstream origin Graphics-Update
...ändringar, add, commit, push...
git branch
git checkout main
git merge Graphics-Update
