# G-Code Stylizer For Notepad++

## How to use the G-CODE stylizer
Download the G-CODE.xml file.\
In Notepad++:
- Click 'Language'
- Go down to 'User Defined Language'
- Click 'Import' and navigate to the xml file and select it.
- In the dropdown menu, select G-CODE
- Add your G-Code file extensions to the 'Ext.' field seperated by a space. 'nc mpf eia gcd txt cam' are already populated.
- Click 'Save As...'
- Give it a name like 'G-Code'

Your files should automatically revert to this color scheme. If not, you may have to go up to Language and navigate down and select G-Code(or whatever you called it)

## Sample
![G-Code Sample](/images/sample.png)


## Dark Mode variant
NOTE: This user defined language is meant to be paired with the Dracula theme which you can find here: <https://draculatheme.com/notepad-plus-plus>
If you use this with any other theme, it probably will look like garbage. Of course, you can always modify the User Defined XML to suit your needs using the Notepad++ built in language stylizer. Since G-Code isn't really a coding language with proper definitions relating to key words, this is the only way I have found to make this work.

### How to use the Dark variant
- Download the Dracula theme and place the XML in your C:\Users\<your username>\AppData\Roaming\Notepad++\themes\ folder. (if the folder isn't there, just create it)
- Download the G-CODE-DARK.xml file from here.
- Open Notepad++
- Go to Settings -> Preferences and select Dark Mode on the left and activate it. (restart Np++ if you need to)
- Go to Settings -> Style Configurator and set it to Dracula.
- Click Save & Close
- Go to Language -> User Defined Language
- Click 'Import' and navigate to the G-CODE-DARK.xml file and select it.
- In the dropdown menu, select G-CODE-DRAK
- Add your G-Code file extensions to the 'Ext.' field seperated by a space. 'nc mpf eia gcd txt cam' are already populated.
- Click 'Save As...'
- Give it a name like 'G-Code-Dark'
Note: There is a wierd bug where sometimes once you import the UDL, it won't show up in the dropdown Languages menu in the navigation bar. And saving it creates a duplicate. not sure why this is, but it seems like a Notepad++ 'bug'.

### Dark Mode Sample
![G-CODE-DARK](/images/Dark_Screenshot.png)
