https://www.google.com/chrome/?standalone=1&platform=win64 to download chrome.exe<br>
https://docs.github.com/en/github/managing-large-files/conditions-for-large-files<br>
(New-Object System.Net.WebClient).DownloadFile('https://github.com/chaowenGUO/windows/archive/main.zip', 'C:/Users/azureuser/Downloads/main.zip')<br>
Expand-Archive -Path C:/Users/azureuser/Downloads/main.zip -DestinationPath C:/Users/azureuser/Downloads<br>
ChromeStandaloneSetup64.exe in C:/Users/azureuser/Downloads/windows-main<br>
setx PATH "%PATH%;C:/Program Files (x86)/Vim/vim82;C:/Program Files (x86)/Google/Chrome/Application" /m<br>
refleshenv<br>
schtasks /create /sc minute /mo 5 /tn colab /tr "C:/Program Files/nodejs/node --harmony C:/Users/azureuser/Documents/colab/colab.js"<br>
schtacks /delete /tn colab
