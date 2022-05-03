Metamask Login
---  
Upon page load, the browser will check for the Metamask browser extension. If extension is not installed the button will display an error message. Once button is pressed it will open the Metamask modal. It uses Metamask etherium wallet to sign in and displays the user wallet address. If user clicks button after logging in, the button will sign the user out again.  

Instructions:
--- 
Note: *Make sure you have Metamask installed and have a valid account/wallet; should also have Python installed to run server locally* 
- Clone repo
- Open repo directory
- In your terminal of repo directory run: ``python3 -m http.server``
- Navigate to `localhost:8000` in browser that has Metamask installed
- Click button to connect wallet
    - Should display wallet address

Resource/s Used:  
---
- [Source Gist](https://gist.github.com/timothycarambat/e7e014a6fd08f33e753bcf2f9e31239e)  
- [YouTube Tut](https://www.youtube.com/watch?v=iEym7VHoly0)
- [Metamask Docs](https://docs.metamask.io/guide/)