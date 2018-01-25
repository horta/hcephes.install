# hcephes.install

One-liner for hcephes installation.

# Usage

For Windows
```
powershell -Command "(New-Object Net.WebClient).DownloadFile('https://raw.githubusercontent.com/limix/hcephes/master/install.bat', 'install.bat')" && install.bat
```

For Linux and macOS
```
bash <(curl -fsSL https://raw.githubusercontent.com/limix/hcephes/master/install)
```
