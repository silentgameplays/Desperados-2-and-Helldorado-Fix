# Desperados 2 and Helldorado Fix
 Desperados 2 and Helldorado Fix
 
1. Go to Control Panel>Programs>Programs and Features>Turn Windows Features on or off>Legacy Components>Enable Direct Play .NET 3.5 Framework support

2. Install Borderless Gaming

3. Install Game and try launching it will crash with "Unable to initialize video mode" error.

4. Find the settings.xml file in C:\Program Files (x86)\Steam\steamapps\common\Desperados 2\data\configuration  or C:\Program Files (x86)\Steam\steamapps\common\Helldorado\data\configuration and edit it with notepad 

# Search for:

 <Attribute name="ENGINE_FULLSCREEN" value="1" type="slong" />

<Attribute name="ENGINE_RESOLUTION_X" value="1024" type="string"/>

< Attribute name="ENGINE_RESOLUTION_Y" value="768" type="string"/>

# Change these attributes to: 

<Attribute name="ENGINE_FULLSCREEN" value="0" type="slong" />

<Attribute name="ENGINE_RESOLUTION_X" value="1920" type="slong"/>

<Attribute name="ENGINE_RESOLUTION_Y" value="1080" type="slong"/>

5. Launch Borderless Gaming

6. Add Desperados and Helldorado to the app

7. Enjoy the game.

# For Linux there is no need for these workarounds both games work fine with Wine/Proton via Lutris/Steam

