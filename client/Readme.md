# Here I have implemented the following:

Now our problem is how to get all the message from their previous chats:

1. First we have made a route called getMessageRoute.js in APIRoutes.js file
2. I have made a div and the className is chat-message and then we have mapped over allthe messages
3. I have implemented a useEffect hook and in there I have called the getMessageRoute api with post method and passed 
the id of currentChat and currentUser
4. We have saved the response in a useState called message

# And Now We can see the message of currentUser and their corresponding chat. 

