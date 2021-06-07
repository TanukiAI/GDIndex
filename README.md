# GDIndex
A better and simpler Google Colab Python Script to Backup a GoIndex Repository

It can download the full index website or just a particular folder

# HOW TO USE
1. Go to https://colab.research.google.com/github/TA40/GDIndex/blob/main/GDIndex.ipynb

2. Run first block

3. Replace the values of the following strings in the 2nd block: _goindex_url, _gdfolderid (Optional: http_auth, goindex_password)

4. Run 2nd block

5. It will ask you to login with your Google Account -> Click the link -> Copy and Paste the Authorization Code and press Enter

6. Press F12 -> Go to Console Tab -> Paste the following code -> Press Enter:
```js
function ClickConnect(){
    console.log("Clicked on connect button"); 
    document.querySelector("colab-connect-button").click()
}
setInterval(ClickConnect,60000)```
