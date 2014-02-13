#PowerPoint Dome Template
**Version 1.1** - Released Feb 13, 2013  
by Andrew Hazelden

![PowerPoint Dome Template Screenshot](Notes/Screenshots/domemaster_slide.jpg)


About the Software
-----------------
The PowerPoint Dome Template provides a simple and effective way to create fulldome formatted presentations. The PowerPoint template comes with 14 "dome optimized" slide layouts. You can use the template file with Microsoft PowerPoint, Google Docs, and LibreOffice.

The PowerPoint template file is a 2:1 aspect ratio document that covers a 360 degree x 90 degree field of view. If your dome projection system allows you to display panoramic imagery directly you can use the Powerpoint generated .PNG or .JPG slides without any extra image processing.

The software is available as a free download. If you find the Dome template useful you are encouraged to consider a small donation to promote further development, and pay bandwidth costs.

![PowerPoint Dome Template Screenshot](Notes/Screenshots/powerpoint_dome_template_960px.png)


#Exporting PowerPoint Slides

You can use PowerPoint to export your presentation to a series of JPG or PNG slides.

##Step 1. Export the Slides
Start by selecting the Export menu item.

##Step 2. Choose a File Type
Click on the "Change File Type" menu item and select either the PNG or JPEG option.

![Export the Slides to a file](Notes/Screenshots/export_png_images_of_the_slides.png)

##Step 3. Save the Slides to a Folder
Click the Save As button to export your slides. PowerPoint will ask you to select an output directory for the images.

![Save the slides to your hard disk](Notes/Screenshots/save_the_slides_to_a_folder.png)

##Step 4. Choose What Slides to Export
To export all of the slides in your presentation choose the "All Slides" button during the save process.

![Export All of the Slides](Notes/Screenshots/export_all_of_the_slides.png)


-----------------

#Maximizing the Export Resolution
It is possible to boost the maximum PowerPoint slide export resolution using the Windows Registry Editor. You can read the guide on the [Microsoft support site: How to change the resolution of a slide that you export as a picture in PowerPoint](http://support.microsoft.com/kb/827745?wa=wsignin1.0).

![Boosting the Export Resolution](Notes/Screenshots/changing_the_export_resolution.png)


##PowerPoint Video Export 
Microsoft's PowerPoint 2013 software allows you to export your presentation to a 1440x720 resolution MPEG4 video file. The PowerPoint video export feature can export your PowerPoint shows to a video file with custom slide timing, animated transitions, and audio narrations.

To export your PowerPoint dome presentation to a video file, open the Export screen and choose "Create a Video". Selecting the "Computer & HD Displays" option will enable the 1440x720p video format.

![PowerPoint Video Export](Notes/Screenshots/powerpoint_create_video.png)

-----------------

#Photoshop Action Installation

The PowerPoint Dome Template comes with a bonus Photoshop action and droplet program for converting your PowerPoint exported .PNG or .JPG slides into angular fisheye formatted "domemaster" images.

![Photoshop Conversion Tools](Notes/Screenshots/photoshop_conversion_tools.png)

#Droplet Usage

If you have Adobe Photoshop installed on your system you can use the included droplet program called "PowerPoint to Domemaster Convert.exe" that is located in the "Conversion tools" folder. The "PowerPoint to Domemaster Convert.exe" program is run by dragging either a single image or a folder of .PNG or .JPG images onto the program icon. The droplet will start Adobe Photoshop and begin processing the images.

**Droplet Tip:** If you have multiple version of Photoshop installed on your system, it is a good idea to start your preferred version of Photoshop first, before you run the droplet. This will tell the droplet to use the active copy of photoshop to process your fulldome imagery.

The droplet starts with the PowerPoint exported slides in either PNG or JPEG format.
![The droplet starts with rectangular images.](Notes/Screenshots/droplet_input_slides.png)

After the images are run throught the droplet they are converted to angular fisheye formatted domemaster images.  
![The droplet starts with rectangular images.](Notes/Screenshots/droplet_output_domemaster_slides.png)

##Droplet Note:  
You should always run the droplet on a copy of your PowerPoint images because the droplet works by converting the original images into the domemaster projection and then saves the result by overwriting the original file.

#Photoshop Actions Installation

##Step 1. Open the Actions Tab

Start by opening Adobe Photoshop. Navigate to the "Window" menu, and select the "Actions" menu item.


![Open the Actions Tab](Notes/Screenshots/photoshop_actions_menu.png)

##Step 2. Load the actions.

Click on the Actions tab pop-up menu located at the top right of the actions tab.

Select the "Load Actions" menu item to import the actions file.

In the Load dialogue window open the folder named "Conversion Tools" and select the action files "PowerPoint Dome Conversions.atn".

Click the Load button to open the action files. The new action will be loaded into the Actions Tab.

![Conversion Actions](Notes/Screenshots/photoshop_conversion_actions.png)

##Step 3. Switch to Button Mode

If you want to make it easier to run the actions you can switch the Actions tab to "Button Mode". This will make each action item a clickable button.

Click on the actions tab pop-up menu located at the top right of the actions tab.

Select the first item in the menu labeled "Button Mode". Your view will switch from a long list into a colourful grid of labeled buttons.


![Photoshop Actions Tab](Notes/Screenshots/photoshop_conversion_actions_as_buttons.png)

To make it easier to find things, the "PowerPoint Dome Conversions" actions are coloured blue. 

You now have two actions to choose from:
  > PowerPoint to Domemaster  
  > Domemaster to PowerPoint

#Photoshop Action Results
Here are two screenshots that show the results of running the PowerPoint Dome Conversions actions in Photoshop.

PowerPoint Exported Slide:  
![PowerPoint Slide](Notes/Screenshots/photoshop_powerpoint_conversion.png)

Domemaster Converted Slide:  
![PowerPoint to Domemaster Conversion result](Notes/Screenshots/photoshop_domemaster_conversion.png)

## Creating a Droplet ##

The updated PowerPoint Dome Template now includes a Mac CS6, and Windows CS2 and CS6 droplets. Here is a tip on creating your own conversion droplet if you are using a different version of Photoshop.

**Step 1.** Follow the instructions in the "Photoshop Actions Installation" section and load the action file "PowerPoint Dome Conversions.atn" into your copy of Photoshop.

**Step 2.** From the File menu, select Automate > Create Droplet...

![Select the Create Droplet menu item](Notes\Screenshots\create-droplet-menu.png)

**Step 3.** The Create Droplet window will open. Click the **Choose...** button to pick a folder location where the droplet will be save. Give the droplet a name like "PowerPoint to Domemaster Convert".

![Choose the Powerpoint to Dome action](Notes\Screenshots\save-droplet.png)

In the **Play** section of the Create Droplet window open the **Set:** popup menu and chose "PowerPoint Dome Conversions". This set is only listed here if you installed the actions file "PowerPoint Dome Conversions.atn" mentioned in step 1.

In the **Action:** Popup menu select "PowerPoint to Domemaster". This will tell the droplet to run the custom action that creates a domemaster formatted image when the droplet is started.

Enable the **Suppress File Open Options Dialogs** and **Suppress Color Profile Warnings** checkboxes so you don't have to click through lots of open dialog messages when you run the droplet.

Set the Destination to **Save And Close**. This will tell the droplet to save the converted imagery over the original file.


Click the "OK" button to create the new droplet.

You now have a custom droplet that was created to match your exact version of Photoshop.

------------------------------------------------------

PowerPoint Dome Template Created by Andrew Hazelden. (c) copyright 2013-2014.

Email: [andrew@andrewhazelden.com](mailto:andrew@andrewhazelden.com)

Blog: [http://www.andrewhazelden.com](http://www.andrewhazelden.com)
