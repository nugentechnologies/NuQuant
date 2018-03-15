# NuGEN NuQuant Assay for Qubit

![http://www.nugen.com](https://www.nugen.com/sites/default/files/logo_0.png)  
[www.nugen.com](http://www.nugen.com)

## Downloading the application

Download the most recent release [here](https://github.com/nugentechnologies/NuQuant/archive/0.0.zip). Unpack the .zip archive after downloading it. (For more information about how to unpack a .zip file, see [here](https://www.wikihow.com/Unzip-a-File).)

### Installing NuQuant on Qubit 2.0

**Note:** NuQuant can only be implemented on Qubit® 2.0 Fluorometers running firmware v3.11 (or higher). For instruments requiring an upgrade, see firmware upgrade instructions [here](https://www.thermofisher.com/us/en/home/industrial/spectroscopy-elemental-isotope-analysis/molecular-spectroscopy/fluorometers/qubit/qubit-technical-resources/previous-qubit-models/qubit-firmware.html).

  1. After downloading the file `Q2CeleroPCRv1.qbt` from the above link, copy it to the root directory of a USB drive (do NOT place the `.qbt` file into a folder in the USB drive). 
     - **Important:** Make sure there is only one `.qbt` file saved to the root directory of the USB drive. Having multiple `.qbt` files present on the USB drive will result in an error when uploading the file.
  2.	Unplug the Qubit power source, insert the USB drive containing the `Q2CeleroPCRv1.qbt` file into the USB drive port of the Qubit® 2.0 Fluorometer, and plug the power back in.
  3.	You will see the message *"Q2CeleroPCRv1.qbt file detected. Do you wish to upload?"* Select `Yes`.
  4.	On the home screen you will now see a button marked `Celero PCR`. Select this to perform the NuQuant assay for Celero PCR library products.


### Installing NuQuant on Qubit 3.0 and Qubit 4

  1. After downloading the file `Q3andQ4CeleroPCRv1.qbt` from the above link, copy it to the root directory of a USB drive (do NOT place the `.qbt` file into a folder in the USB drive). 
     - **Important:** Make sure there is only one `.qbt` file saved to the root directory of the USB drive. Having multiple `.qbt` files present on the USB drive will result in an error when uploading the file.    
  2. Insert the USB drive into the USB drive port of the Qubit® 3.0 or Qubit® 4 Fluorometer. 
  3. Go to the Settings screen and touch `Import new assay`. The instrument searches the USB drive for the `.qbt` file and the Import new assay screen displays "Celero PCR NuQuant v1.0" under Assay name.
  4. Touch to “Celero PCR NuQuant v1.0” to select. It will become highlighted. Touch `Next`.
     - Option A: Select a destination folder for the new assay and touch `Save`. Each folder can hold up to 9 assays.
  
     - Option B: Alternatively, touch `New folder` to create a new destination folder. On the New folder screen, touch the `New folder` text field. A keyboard pops up. Using the keyboard, type in the name of the new destination folder. You can use up to 11 characters; spaces at the beginning or the end of the name are not recognized. Touch `Enter`, and then touch `Done` to return to the "Import new assay – Where" screen. The newly created folder will appear in the list of folders. Select the new destination folder and touch `Save`.
  5.	On the verification screen, touch `Done` to complete the import process.
  6.	On the home screen you will now see a button marked Celero PCR. Select this to perform the NuQuant assay for Celero PCR library products.


### Uninstalling NuQuant on Qubit 2.0

If you wish to remove NuQuant, including the `Celero PCR` button from your Qubit home screen, perform the following steps:

  1.	Follow the steps for upgrading firmware (see firmware upgrade instructions.)
  2.	Once you press the `Update` button, a message will appear titled “Updating: Select Assay(s) to Delete”. Select `Celero PCR`. The *Celero PCR* line will turn gray, indicating it has been selected.
  3.	Click `OK`. 
  4.	Another window will appear with the message *“The selected assay(s) will be deleted. Do you wish to proceed?”*  Click `Yes`. 
  5.	The “Updating firmware…” status bar will appear. After approximately 1 minute, the update will be complete and the NuGEN NuQuant app will have been removed.

### Uninstalling NuQuant from Qubit 3.0 and Qubit 4

  1.	Go to the Settings screen and touch Manage assays.
  2.	Touch `Show/hide Assays`.
  3.  Select the folder which contains NuQuant.
  4.  Next to *CeleroPCR NuQuant v1.0*, touch `Delete`, then `Done`.
  5.	The next screen will ask *“This will permanently delete the selected assay(s). Do you wish to continue?"* Touch `OK`.
