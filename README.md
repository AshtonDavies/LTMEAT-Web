# <img width="22px" src="https://ltmeat.bypassi.com/img/icon.png"> LTMEAT</img>
Web version of LTMEAT, another exploit discovered by Bypassi#7037 to bypass admin-forced extensions on managed Chromebooks.
# <img width="500px" src="https://github.com/AshtonDavies/LTMEAT/blob/main/screenshot.png?raw=true"></img>
# Patched
LTMEAT was patched in <b>Chrome OS 115</b> on May 23, 2023 (dev).
<p>
Many Chrome debug commands such as <em>chrome://kill</em> and <em>chrome://hang</em> no longer work on managed accounts.
<p>
<b><ins>How to bypass the LTMEAT patch:</ins></b>
<ol>
<li>Add a new folder to your bookmarks bar.</li>
<li>In the folder, add the extension settings url of the extension you want to freeze (chrome://extensions/?id=<em>extensionid</em>).</li>
<li>Add the background or manifest page of the extension to the folder (chrome-extension://<em>extensionid</em>/_generated_background_page.html) and paste it 800+ times (enough to make browser loading very slow).</li>
<li>Open the entire folder in a new window, which can be done by right-clicking it in the bookmarks bar and selecting that option.</li>
<li>Close the window that was just opened.</li>
<li>Open the folder in a new window again. The pages will be hanged by Chrome as if the tabs were duplicated from hanged ones.</li>
<li>Flip the <em>Allow access to file URLs</em> switch in the extension settings.</li>
</ol>

# How to Use
Done similar to the official instructions. If stuck, click the buttons for help messages or read the official documentation.

<img width="500px" src="https://github.com/AshtonDavies/LTMEAT/blob/main/tutorial.gif?raw=true"></img>

# About
Designed to be a simple, pre-setup place to activate LTMEAT without the use of bookmarks or manifest pages. Contains common web filter links to drag and drop.
<p><b>Official Site:</b> https://ltmeat.bypassi.com
