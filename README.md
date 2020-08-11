# Welcome to colab-to-drive!

> If you need a backup of your local data on **Google Drive** it might be an **Ultimate Solution**. Here we will Upload a file from **local computer** to **Google Colab** and move those file to our destination like **Google Drive**.  We will be able to move those file to  **Shared Drive** too.

For this workflow we need a **Google Account** and **Internet connetion**. As [Google Colab](https://colab.research.google.com/) is a free service we can get this with general  Google Account. Google Colab will move our files without using our own internet bandwidth. Whole process is totally free. 

## Workflow
1. First of all open **[Google Colab](https://colab.research.google.com/)** in a browser. Sign in with your Google Account (if needed)
2. Run 1st cell to Mount Google Drive (ignore warning, just click **RUN ANYWAY**).  Click on the link that appeared. Select the **Google Account** in which you want to backup your files. **Allow** then copy the code and paste it in colab notebook. 
3. Now it's time to **Upload Local Files**. Run 2nd cell. **Choose Files** that you want to backup.
4. Now hover your cursor to the left menu bar. There you will find a **Files** menu. Click on it and find **Content**. Click on the three dot of file that you uploaded and **copy path**. Paste the path on **source**.
5. Now find **gdrive** on files. Copy path of your  destination folder and paste the path on **dest**.
6. Now Run 3rd cell. This will move your file to Google Drive. When it's done, it will show the moved file path. 
7. Now your are done!

## Points to be noted
* Here you can only upload **Files**, not any **Folder**. For uploading a whole **Folder** you have to zip that Folder. Then this will be uploaded. 
* You shouldn't upload very large file. This will took too much time to process. Sometime it might ask for reconnect. 
* While 3rd cell is running don't close the browser/stop the process. This might hamper your data.
