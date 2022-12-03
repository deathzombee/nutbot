## Nutbot
> nutbot is a simple discord bot using discordgo currently using most of the code from the discordgo example airhorn  
> the biggest differences are that I've added context to select which .dca to load into the buffer based on the command  
> of course since the buffer is global and with more than one file this if we did not clear it after each command it would  
> keep adding to the buffer and play the entire thing, so I've added in a quick buffer clear. 

## Usage
- make sure you have Message Content Intent enabled in your bot settings
- grab a token from the discord developer portal and 
- run the bot with -t <token\>