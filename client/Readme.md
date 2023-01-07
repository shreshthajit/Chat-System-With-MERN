# Here I have implemented the following:
 1. I have created ChatInput.js file and saved it in ChatContainer.js file
 2. In ChatInput.js file I have made a form where we will type our message and button for sending message.
 3. I have created Messages.js file and save it to ChatContaner.js file
 4. in ChatInput.js file we have implemented functionalities for taking our 
 desired emoji
 5. So basically in this commit we have implemented ChatInput.js file with differnt functionalities.


 # npm install emoji-picker-react

 ## an error that I faced is described below when loading an emoji:
 onEmojiClick prop receives a "callback function that is called when an emoji is clicked. The function receives the emoji object as a parameter."
 onEmojiClick: (emojiData: EmojiClickData, event: MouseEvent) => void

 with the 1st argument being the emoji object and the 2nd argument being the event. In our handleEmojiClick I was doing the opposite order and that's why it returns undefined.


