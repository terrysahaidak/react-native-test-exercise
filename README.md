# React native candidats test exercise
> by Terry Sahaidak ([terry@sahaidak.com](terry@sahaidak.com))
--------

### Requirements for development environment

1. Expo.io is used.
2. Configured eslint.
3. React Navigation is used for navigation.
4. No ui-toolkits and libs are used. Only your styles and components.

### Also, would be good if:

1. You're familiar with recompose.
2. You won't live without redux.
3. You're in love with reselect.
4. Ramda and functional approach is your life.
5. Mobx and GraphQL aren't empty sounds for you.

## Exercise descriptions

You should build a chat application with the following screens:
1. Chats list
2. Сhat
3. User

### Chat list screen requirements

1. It should be list of chats.
2. Each chat item should have participant's avatar and name, the last message time and text, also, read/unread status.
3. After taping to chat item apps navigate us to chat screen.
4. After long tap it shows pop-up with delete action.
5. We should be able to filter all chats by texting user name. (\*)

_\* is note required, but would be a big bonus for you._

### Chat screen requirements

1. Each message should displays inside the bubble (iMessage-like gray-blue clouds).
2. Participant messages should be displayed in the left side inside gray bubble.
3. Our messages should be displayed in the right side inside blue bubble.
4. Messages can have state field (read, don't send, sending, delivered etc).
5. Messages should be grouped by interval of time (group it if the interval between messages is bigger that 10m).
6. Each group should be separated by sticky section header.
7. Message input component should contain message input itselft, send button, camera and galary icon-buttons.
8. Message input should send messages and displays it as a new message.
9. We should be abble to navigate to user screen.
9. Custom header with user avatar, name, online status. (\*)
10. Edit/delete message actions. (\*)
11. Send and displays photos from galery and camera. (\*)
12. Typing status. (\*)
13. Message input expand/collapse animation (\*\*)

_\* is note required, but each of this tasks would be a big bonus for you._

_\*\* SUPER BONUS!!!_

### User screen requirements

1. Display some user's info such as avatar, name, online status.
2. There should be some action buttons like block user, delete chat.
3. Display user avatar in modal.
4. Implement block user action with some ux/ui. (\*)
5. Implement delete chat action with some ux for it. (\*)

_\* is note required, but each of this tasks would be a big bonus for you._

## YOU ARE DEFINITELY OUR PERSON IF YOU WILL:

1. Use redux/mobx for state managment.
2. Implement and deploy to some cloud back-end for chat application.
3. Use socket.io or faye for realtime chat updates.
4. Use some oauth authorization (Google, Facebook, Twitter etc).
