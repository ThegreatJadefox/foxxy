
# _➥ Welcome message setup_
## _• You can set welcome message in many ways._
### _~ Given below are some elements which can be added in any welcome message types._
_{group-name} : Displays group name_
<br>
_{group-desc} : Displays group description_
<br>
_{count} : Displays current group members count_
<br>
_{mention} : Mentions the person joined_
<br>
_& : Adds one line break (enter key)_
<br>
## _➥ Types of normal welcome message_
### • Welcome message with custom image
* Add a image link such as https://i.imgur.com/st4R2dq.jpeg in welcome message to display the custom image. Example:
> .Welcome https://i.imgur.com/st4R2dq.jpeg Hey {mention}, welcome to {group-name}
### Welcome message with custom video
* Add a video link such as https://i.imgur.com/UosqtuO.mp4 in welcome message to display the custom video. Example:
> .Welcome https://i.imgur.com/UosqtuO.mp4 Hey {mention}, welcome to {group-name}
### Welcome message with joined member's profile picture
* Add a {pp} element in welcome message to display the profile pic. Example:
> .Welcome {pp} Hey {mention}, welcome to {group-name}
### Welcome message with group icon
* Add a element {gicon} in welcome message to display the current group's icon image. Example:
> .Welcome {gicon} Hey {mention}, welcome to {group-name}

**Of course, you can add all the elements in the message. use .url command to get media URLs!**
## Types of button welcome messages
### Some important elements in button welcome message
#button\Hey#
<br>
#ubutton\Click me# #url\https://github.com/souravkl11/raganork-md#
<br>
#footer\Server status: OK#
<br>
#cbutton\Contact Owner# #num\+91 6282344739#
## 🛑 Important advice regarded to button welcome message 🛑
### As per the default limitations of WhatsApp, You can only add up to 5 buttons in a single message. Like 2 Url Button and 3 Reply buttons, 1 call button & url button and 3 reply buttons. Example for this is given below
### Mode 1 (With two urls and 3 reply buttons):
> {pp} Hey {mention} Welcome to {group-name} & {group-desc} & {count}/257 members Joined in this group & Do you love me? #button\𝗬𝗘𝗦 ✅# #button\𝗡𝗢𝗣𝗘 ‼# #button\How r u?#  #ubutton\Follow me on Instsgram# #url\http://www.instagram.com/sou6av##footer\Server status: OK##ubutton\Whatsapp# #url\https://wa.me/916282344739?text=Lub+U+Vro+😻#
### Mode 2 (With 1 call, 1 url and 3 reply buttons):
> {pp} Hey {mention} Welcome to {group-name} & {group-desc} & {count}/257 members Joined in this group & Do you love me? #button\𝗬𝗘𝗦 ✅# #button\𝗡𝗢𝗣𝗘 ‼# #button\How r u?#  #cbutton\Contact owner# #num\+916282344739# #ubutton\Whatsapp##footer\Server status: OK##url\https://wa.me/916282344739?text=Lub+U+Vro+😻#
## I hope you had understood anything that I said above!. Use your own logic and create more messages with your creativity. As I said above, you can use image links and {gicon} in button welcomes except video! You can set filters for replying to the buttons :)